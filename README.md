# Dual-Band-Limiter - JSFX
Dual-Band Limiter written in Reapers JSFX

A Very simple Dual-Band Limiter. Uses classic RJB Bi-Quads to split the signal into two, and process each band separately. Using overlapp and add with a cosine blend to smooth any drastic limit level changes - works really well. Has a super fast Hi-Res FFT - uses a small fifo stack into a Large FFT for fast response times and then gaussian smooth for slick lower frequency display. Added a 3 band pre-eq for gutiar - boost the bass and it will act like a noise reduction system - since the bass limiting will hide alot of the hi-freq noise.

Left some half-assed "cloner" system in there - tries to detect guitar picking and clone the signal with delays to give a big wide "Multi-Tracked" sound. Didn't work at all - sounds like a right old mess - hahhah.

Also added a "Draw Freq" option - tries to identify peaks in the lower end of the FFT and displays the HZ - works, a little messy tho.

"Post EQ" has no code - so it doesn't do anything, might add a 5 band eq later.

In-Gain - will boost the lower or upper bands and force more aggressive limiting, great for metal \m/ .

Out-Gain controls the band output level after limiting.

Release-Time controls the release time for both limiters, using the Time-Constant math, probably very wrong.

Mouse drag to move the pre-eq Control points and Mouse Wheel to change the Q/Bandwidth.

Mouse drag the yellow circle on the lower part of the screen to change the dual-band freq split, no Q/Bandwidth control on that one.

![](./Images/Image1.png)
