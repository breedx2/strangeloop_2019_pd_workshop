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

[prev](../07_Enough_already_more_noises/) |
[top](https://github.com/breedx2/strangeloop_2019_pd_workshop) |
[next](../09_Filtered_noise/) 
