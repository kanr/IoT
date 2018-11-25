# Links and notes

rapid prototyping
[research based design approach](https://en.wikipedia.org/wiki/Research-based_design)




Docs
[Nick O'Leary on node-red + Balena.io (formerly resin)](https://medium.com/@knolleary/deploying-node-red-applications-to-devices-using-resin-io-58d2042cdb0c)
[Related Forum post](https://forums.balena.io/t/deploying-node-red-applications-to-devices/4068)

[Slide Share](https://www.slideshare.net/resin_io)



## Thoughts

I promise to be thoughtful and attentive to the correctness of my decisions and recommendations regarding technology. This is crucial in my field since the impact to the business could be tremendous both in positive and negative ways.

> Werner heisnberg: an expert is someone who can avoid making the worst mistakes in their field.

## Balena + Platformio

Taking advantage of Balena.io with arduinos and other micro controllers as extensions for single board computers like the raspberry pi would enable users to build custom industrial control systems.

There are a couple of promising examples that I have begun exploring. The examples below use make to compile and upload the arduino sketches.

Balena is experimenting with this idea in their platform.

https://github.com/balena-io-projects/balena-arduino-programmer
https://github.com/j3tm0t0/arduberry

This example(s) is using the platormio compiler to build and flash the microcontroller.

Updating and patching smart devices in the home is a critical part of making IoT more secure.
https://github.com/balena-io-playground/esp8266-dht

### Market Research and equivalent products

[N8 controls Austin, TX](https://www.natecontrols.com/)

[GrowNetics Bolder, CO]
<http://grownetics.co/product/res-sensor01/>
<http://grownetics.co/software-services/>