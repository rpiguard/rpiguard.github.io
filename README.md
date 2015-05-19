# Why
If you need to install a security camera system today you have these option:
- buy some cheap stuff that will let you down when you need it
- buy more expensive stuff (a few hundred dollars) that is more robust, but still does little more than taking some recordings and sending you an email or uploading a picture via ftp. Often these cameras won't deliver the advertised performances and get extremely laggy if you crank up the megapixels to what they are supposed to support
- buy crazy expensive stuff (several hundred dollars up to a thousand+ for some PTZ domes) which will actually do what it says
- for the cheaper stuff you often need to budget for control boxes if you want to store video recordings or do motion detection.

But most of all, they are all black boxes.
* Want to turn on the light if a camera detection motion? not possible.
* Want to call you on the phone if the front door is open? not possible.
* Want to get your videos straight to dropbox or gdrive? not possible.

Some more expensive stuff will have cloud integrations, but it's often a proprietary product and you cannot use what you already have.

With the advent of the Raspberry Pi camera we thought it should be possible to build high grade security camera. However it's not as easy as slapping the camera on the pi and installing something like Motion. That might work if you're trying to record the neighbor stealing your mail, but won't cut it for anything more serious.

# Goal
Build a high grade security camera that's capable of:
* day and night vision (infrared)
* detect motion and do face detection
* record high quality videos of intrusions
* interface with whatever storage service (cloud or not) you might have for archival
* provide an api to interface the camera to other sensors and services
* integrate the camera with 3rd party services such as twilio to alert you via sms or phone call

# Status
We're still in a proof of concept phase with lots of scripts and prototypes kicking around. We're gathering momentum and putting it all together to be released. Feel free to drop us an email if you want more info at smile@rpiguard.com

# Authors and Contributors
xab, Don, Kelv, Spike

# Support or Contact
For anything hit us on [twitter](http://twitter.com/rpiguard) or drop us an email at smile@rpiguard.com
