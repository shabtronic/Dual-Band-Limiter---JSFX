# Dual-Band-Limiter - JSFX
Dual-Band Limiter written in Reapers JSFX

A Very simple Dual-Band Limiter. Uses classic RJB Bi-Quads to split the signal into two, and process each band separately. Using overlapp and add with a cosine blend to smooth any drastic limit level changes - works really well. Has a super fast Hi-Res FFT - uses a small fifo stack into a Large FTT for fast response times and then gaussian smooth for slick lower frequency display.

![](./Images/Image1.png)
