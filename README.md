Keepon-Drumming
===============

A simple drum pattern sequencer that interacts with a toy robot.

Written primarily in JavaScript, this project features a 4 row, 8 step drum pattern sequencer that fires Roland TR808 drum samples and loops continuously. It uses D3.js for most of its animation and the Web Audio API to load the sounds. 

Originally inspired by pattern sequencers like Andre Michelle’s ToneMatrix (http://tonematrix.audiotool.com/), this web app is intended to and introduce users to the experience of creating electronic music in an accessible and fun way. 

Ultimately, this project will be taken offline, where it will run entirely off a BeagleBone, using buttons and LEDs rather than the interface currently seen. It will also interact with a hacked MyKeepon robot toy (https://github.com/beatbots/mykeepon, which will respond randomly each time a kick drum is fired. 

Please note, in order to for sounds to work in this app when running the audio files locally, web security in chrome must be disabled using terminal: (open /Applications/Google\ Chrome.app --args --disable-web-security).
