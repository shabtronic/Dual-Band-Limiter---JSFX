# Dual-Band-Limiter - JSFX
Dual-Band Limiter written in Reapers JSFX

A Very simple Dual-Band Limiter. Uses classic RJB Bi-Quads to split the signal into two, and process each band separately. Using overlapp and add with a cosine blend to smooth any drastic limit level changes - works really well. Has a super fast Hi-Res FFT - uses a small fifo stack into a Large FFT for fast response times and then gaussian smooth for slick lower frequency display. Added a 3 band pre-eq for gutiar - boost the bass and it will act like a noise reduction system - since the bass limiting will hide alot of the hi-freq noise.

![](./Images/Image1.png)
