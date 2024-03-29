# Intro
(3 min)

A bit about me:
* I do projects and blog at [noisybox.net](https://noisybox.net)
* I release music as [infiltration lab](https://infiltrationlab.com)
  * You can [hear more at archive.org](https://archive.org/search.php?query=%22infiltration%20lab%22)
* I collaborated on [this project](https://www.parallel.studio/elements-1) ([and more](https://www.youtube.com/watch?v=kDpdnAmAjI4))

Background about pd:
* MILLER (and community!)
* flavors
 * vanilla
 * l2ork
 * extended is eol
 
 I like pd because I like sound and it made me think differently about programming.
 
 This workshop is ____________________________
 * An introductory primer
 * Hopefully some inspiration
 * intended to help you start experimenting with sound
 
 This workshop is not ________________________
 * A turnkey way to make EDM
 * not protools or live(tm)

# Let's Begin!
(5 min)

* main screen
  * a few disclaimers:
  * it's not pretty
  * you will miss features
  * it's very primitive <3
* dsp
* media -> test
* modal editor

# Hello world
(5 min)

* hopefully you have [already installed pd](http://msp.ucsd.edu/software.html)
* hello world (console)
  * change print prefix
* hello world (audio)
  * ouch that's loud! (this happens, promise)

# Patching essentials
(5 minutes)

What did we just do?

* learn all the shortcuts!
* edit mode toggle
* clicking off the object
* selecting
  * box
  * shift click
* number box + ui
  * type it in (plus enter!)
  * shift drag
* hot/quick play
* duplicate
* save your work

# The help system
(5 min)

* how to find help
* browser
  * how it's laid out
* list of objects
* right click most objects

# Some fundamentals
(10 min)

* Terminology
  * inlets / outlets
  * types: bang, float, message, list, signal
  * graphical ui elements
* 2 graphs: audio vs data
  * The tilde (~)
  * adc~, dac~

# More fundamentals
(10 minutes)

* a creation conundrum
  * a number feeding two prints (then changeem)
* hot/cold inlets
  * bad adder example
* build a counter
* how to build 1/x
  * T and f
  * uses [trigger] which is [t]
  
# Enough already, more noises!
(30 min)

Ok, lets do an exercise to expand on what we've learned so far...

* let's do a slow vca
* introducing [vline~]
  * envelope the volume
  * envelope some pitch
* introducing [metro]
  * our counter from before
  * mod 16
* add a table
  * scale the table 
  * add an hradio below
* template that message
* introducing [mtof]
* add a numbox to metro time inlet (wowwy wow!)

# Add some delay
(7 min)

Even some basic delay can enhance your sound.

* [delwrite~ xxx 2500]
* [delread4~ xxx] [vd~] (same thing)
  * add adjust to delay time
* dump read into adjustable [*~]
  * make feedback number max 1
* put into output path with [+~]
* tinker with delay time and feedback amount

# Filtered noise
(10 minutes)

* [lop~]tabwrite~ a2
* [hip~]
* [bp~]
* [vcf~]

# The microphone
(12 min)

* [adc~]
  * the opposite of [dac~]
* arrays/tables and [tabwrite~]
* [tabplay~]
* [tabosc4~]
* [tabread4~]
  * drive first with [vline~]
  * next drive with [phasor~]
    * negative frequency plays backwards

# Getting abstract / reuse
(?? min)

* Subpatches
  * start with `pd `
* Abstractions 
* Externals
* Graph on parent


# MIXEDUP
* order of outlets
* hot vs cold inlets
* vline
* dline
* tables / arrays
* tabosc
* AM
* FM
* filters
* saving/presets?

# Resources
* tbd
