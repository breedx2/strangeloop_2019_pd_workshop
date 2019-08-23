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
(3 minutes)

What did we just do?

* learn all the shortcuts!
* edit mode toggle
* clicking off the object
* selecting
  * box
  * shift click
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
(15 minutes)

Ok, lets expand on what we've learned so far while doing an exercise.

* let's do a slow vca
* introducing [vline~]
  * envelope the volume
  * envelope some pitch
* introducing [metro]
  * our counter from before
  * mod 16
* add a table
  * scale the table 
* add an hradio to metro (wowwy wow)


# Getting abstract / reuse
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
