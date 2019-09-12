# Let's build a simple voice

It's an enveloped oscillator.

* [osc~ 440] into [\*\~] into [dac~]
* add [vline~] to right inlet of [*~]
 * look at [vline~] help
 * send [1 20, 0.8 10 30, 0 5 50 ( into the [vline~]
 
 Now that we have the basic envelope, let's modify the pitch:
 
* [vline~] into the [osc~ 440]
* into the [vline~]: [30, $1 10 30, 50 5 50 (
* and then an hslider that feeds an mtof

[prev](../05_Some_Fundamentals/) |
[top](https://github.com/breedx2/strangeloop_2019_pd_workshop) |
[next](../07_More_Fundamentals/) 
