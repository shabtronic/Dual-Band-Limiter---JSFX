# Dual-Band-Limiter - JSFX
Dual-Band Limiter written in Reapers JSFX

A Very simple Dual-Band Limiter. Uses classic RJB Bi-Quads to split the signal into two, and process each band separately. Using overlapp and add with a cosine blend to smooth any drastic limit level changes - works really well. Has a super fast Hi-Res FFT - uses a small fifo stack into a Large FFT for fast response times and then gaussian smooth for slick lower frequency display. Added a 3 band pre-eq for gutiar - boost the bass and it will act like a noise reduction system - since the bass limiting will hide alot of the hi-freq noise.

Left some half-assed "cloner" system in there - tries to detect guitar picking and clone the signal with delays to give a big wide "Multi-Tracked" sound. Didn't work at all - sounds like a right old mess - hahhah.

Also added a "Draw Freq" option - tries to identify peaks in the lower end of the FFT and displays the HZ - works, a little messy tho.

![](./Images/Image1.png)
