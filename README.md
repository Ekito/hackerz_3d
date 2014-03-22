TrackMyPet - Arduino support
==

About
--

TrackMyPet is a proof of concept of a Sigfox enabled GPS tracked intended to show the last known position of your equiped pet (OK, a big pet, like a pony or a cow; don't try with your hamster).

TrackMyPet is based on the following technologies : 

* GPS Tracker : Ardunio board with [Sigfox modem](http://sigfox.com/) (named [Akeru](http://akeru.cc/), homemade battery shield and MTK3339 GPS module.
* Play! 2.2 application hosted on [Heroku](http://herokuapp.com/) Server and [Kinvey](http://kinvey.com/) datastore for GPS data persistence.


GPS Tracker
--

Head over to the related [GitHub repository](https://github.com/Ekito/hackerz_akeru)!


Server part
--

Head over to the related [GitHub repository](https://github.com/Ekito/hackerz-server)!

You can see “live action” [here](http://hackerz-server.herokuapp.com/)


Arduino support
--

These supports are intended to be fixed to the harness or collar of the animal you want to track. You have two versions: 
* support_arduino_long_thick: This support has the same size than the Akeru board and is 5mm thick. 
* support_arduino_short_thin: This support is slightly shorter than the Akeru board (on antenna side) and is 3mm thick.