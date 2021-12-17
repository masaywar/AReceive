# AReceive

## Abstract
  The AR market is growing. Not only software but also hardware market (for example AR head mount device) is also expected to grow much more than now. for this reason, AR developers have to consider how to make interaction with other devices or users. The developers should make these closely to our physical worlds to give them immersive feeling. So we are progressing on this "AReceive" project for making the users comfortable and intuitive. 

## Feature
  1. We make a couple of applications, The ARecive-Hmd and ARclient.  
  2. These are implemented by [Opencv](https://opencv.org/). 
  3. Feature detecting using [ORB](https://docs.opencv.org/4.x/d1/d89/tutorial_py_orb.html) and [Bruteforce_Hamming](https://docs.opencv.org/4.x/dc/dc3/tutorial_py_matcher.html).
  4. Network architecture is based on Server-client architecture. The AR hmd take part of server and devices, for example mobile etc, are clients.
  
## Limitations
  1. For now, We made just 1:1 server-client matching
  2. It was hard to get feature points as many as we expected.

## TODO
  1. Extend the functions as 1:N relations.
  2. Find other way to get more feature points.
  3. Make API to easy-use for other AR developers.

## ETC
  [Prototype Test video](https://drive.google.com/file/d/1cUuzTOvUPIJ_Knxzx3OLBN2St4olxyTW/view?usp=sharing)
