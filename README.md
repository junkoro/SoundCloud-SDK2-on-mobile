SoundCloud-SDK2-on-mobile
=========================

This sample shows you how to play SoundCloud on mobile browsers using SDK2.


Custom SDK2
-----------

This sample uses custom version of SDK2（ http://connect.soundcloud.com/sdk-2.0.0.js ） and audiomanager（automatically loaded by SDK2）. Because the official version can not play on mobile browsers.


"auto play" problem
-----------------

We can play SoundCloud like this on mobile, but auto play problem exists. We need real user touch to play after loading media.

"Audio files can only be loaded from a user-triggered touch (click) event."

Overcoming iOS HTML5 audio limitations
http://www.ibm.com/developerworks/library/wa-ioshtml5/

Making HTML5 audio actually work on mobile | Pupunzi
http://pupunzi.open-lab.com/2013/03/13/making-html5-audio-actually-work-on-mobile/


SET YOUR OWN CLIENT ID
------------------

If you are going to deploy this sample, you must set the client id in js/index.js.
