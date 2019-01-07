SpeakTyper
==================

This projects reads keys from a ps2 keyboard and speaks them out in the old robot style Speak & Spell voice.


### Backstory

I wanted to make a PS2 keybaord -> speak the letters gadget for my daughter so she can learn her letters (and qwerty I guess?). She loves typing on the keyboard, and I turned on VoiceOver on my mac once, and she loved it! She's had her own keyboard to bang on for a while, but maybe its time it did something interesting.

Sure I could play some wav files, but wouldn't some kind of TTS robot voice be so much cooler?

After initially failing to find any low-end/cheap TTS/speech synthesis things for micros, I found [Talkie](https://github.com/PaulStoffregen/Talkie). My initial search turned up:

* [EMIC2](https://www.parallax.com/product/30016) $60
* [SpeakJet](https://www.sparkfun.com/products/9578) $25
* [µtts](https://hackaday.io/project/3022-tts) - unfinished, no code

Then I stumbled on [Talkie](https://github.com/PaulStoffregen/Talkie), somewhat ironically when I was looking at the Teensy prop shield, which has an audio amp and 8MB flash, enough for some audio files. 

So Talkie is an open source implementation of the old 70/80's style speech synthesis chips used in the Speak & Spell, and even includes a tool that will convert speech into these phoneme/sound bits that compresses very well, if you like sounding like you went through a speak'n'spell filter, like 129 seconds of speech in 24K!


