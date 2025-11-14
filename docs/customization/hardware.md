# Hardware customization

*Making Mixy fully your's*


Mixy has two modes of operation:

 - slow mode
 - fast mode

 The slow/fast terms refer to sampling frequency which directly influences the responsivness of knobs.  
 The higher the frequency, the better response time, but higher battery usage.

 They work like that:

 - start with slow mode (sampling frequency controlled by `Slow Interval`)
 - if knob change is detected, switch to fast mode
 - sampling frequency controlled by `Fast Interval`
 - if no changes detected for `Fast Timeout`, switch back to slow mode

`Change Threshold` parameter controls knob movement sensitivity, usually there is no reason to change it.

Based on above, you should understand that to save battery:

1. `Slow Interval` needs to be high
2. `Fast Interval` also needs to be high
3. while `Fast Timeout` needs to be low

In the future, some kind of calculator/formula will be provided. But for now let's just say that 1. and 3. are much more important.

You can learn how to set these parameters for every program in corresponding setup guide.