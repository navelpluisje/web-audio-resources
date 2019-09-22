# HTML5 Web audio resources

This is a list of curated resources related to the [Web audio API](http://webaudio.github.io/web-audio-api/). Browser support for the web audio API can be found [here](http://caniuse.com/#feat=audio-api).

## Specifications
- [Web audio API Draft](https://webaudio.github.io/web-audio-api/) - The official Web audio API draft version.
- [Web audio API](https://www.w3.org/TR/webaudio/) - The official Web audio API.

## Learning and tutorials
- [MDN Web api documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) - Mozilla documentation for developing with web audio API.
- [AudioWorklet](https://developers.google.com/web/updates/2017/12/audio-worklet) - A Blog post about the audio worklet.
- [Noisehack](http://noisehack.com/) - A Blog about audio programming with plenty of articles about web audio api.
- [Web audio gotchas](https://github.com/Jam3/web-audio-player#webaudio-gotchas) - A small list of tricky web audio gotchas that are much needed to keep sanity.
- [Building a virtual synth pad](http://www.sitepoint.com/html5-web-audio-api-tutorial-building-virtual-synth-pad/) - Tutorial to build a virtual synth pad that will play audio samples and provide a reverb feature.
- [Web audio playground](http://webaudioplayground.appspot.com/) - A graphic builder of an audio context graph. Helps visualize the way connections are made between web audio nodes.
- [Web audio for games](http://www.html5rocks.com/en/tutorials/webaudio/games/) Web audio techniques applied to game development.
- [Peaks.js explained](http://www.bbc.co.uk/rd/blog/2013/10/audio-waveforms) - Article on the development of Peaks.js, an audio waveform rendering tool for the browser.
- [Guitar tuner tutorial](https://aerotwist.com/blog/guitar-tuner/) - Create a guitar tuner with web audio and Polymer
- [Synthesizing tones with Fourier transforms](http://www.sitepoint.com/using-fourier-transforms-web-audio-api/) - Sound generation with oscillators and Fourier transforms.
- [Web MIDI API and Web Audio tutorial](http://www.toptal.com/web/creating-browser-based-audio-applications-controlled-by-midi-hardware) - Basic tutorial to create a simple synthesizer controlled by MIDI hardware.
- [Javascript Air episode on Web Audio](https://javascriptair.com/episodes/2016-07-27/) - An overview at audio programming with JavaScript and an introduction to some tools and frameworks.
- [Slack's web audio channel](https://web-audio-slackin.herokuapp.com/) - A friendly slack channel of people interested in web audio.
- [JavaScript Systems Music](http://teropa.info/blog/2016/07/28/javascript-systems-music.html) - An article by Tero Parviainen on recreating generative music pieces by Steve Reich and Brian Eno.
- [Recreating Legendary 8-bit games music](http://codepen.io/gregh/post/recreating-legendary-8-bit-games-music-with-web-audio-api) - An article on how to use web audio to generate 8-bit music (a.k.a chiptune).

## Libraries
- [Howler.js](https://github.com/goldfire/howler.js) - Web audio library. Falls back to HTML5 Audio.
- [Tone.js](https://github.com/Tonejs/Tone.js) - Framework for creating interactive music in the browser.
- [Wad](https://github.com/rserota/wad) - Library for manipulating audio with web audio.
- [Tuna](https://github.com/Theodeus/tuna) - Audio effects library.
- [Blip](https://github.com/jshanley/blip) - Lightweight web audio wrapper.
- [Pizzicato](https://github.com/alemangui/pizzicato) - A library that aims to simplify the way you create and manipulate sounds with the Web Audio API.
- [Soundio](https://github.com/soundio/soundio) - Soundio is a Graph Object Model for Web Audio processing graphs. It also provides a JSONify-able structure for exporting and importing them.
- [Theresa's sound world](https://github.com/stuartmemo/theresas-sound-world) - Library for manipulating audio built on top of the web audio API.
- [Musical](https://github.com/PencilCode/musical.js) - A light library with a sequencing synthesizer that supports ABC notation.
- [virtual-audio-graph](https://github.com/benji6/virtual-audio-graph) - Library for declaratively manipulating the Web Audio API.
- [gibber.lib.js](http://charlie-roberts.com/gibber/gibber-lib-js) - Library version of [Gibber](http://gibber.mat.ucsb.edu)
- [XSound](https://github.com/Korilakkuma/XSound) - Web Audio API Library for Synths, Visualization, Effects ... etc

## Visualization
- [Wavesurfer.js](http://wavesurfer-js.org/) - Waveform audio visualization built on top of Web Audio API and HTML5 Canvas.
- [Peaks.js](https://github.com/bbcrd/peaks.js) - JavaScript UI component created by the BBC for interacting with waveforms.
- [Party mode](https://github.com/preziotte/party-mode) - An audio visualizer powered by d3.js and the web audio api.
- [Audiograph](http://audiograph.xyz/) - A visualization of Pilotpriest'S 2016 album and one of the winners of the Dolby Web Challenge.
- [Web Audio Inspector](https://github.com/google/audion) - A debugging tool that visualizes the Web Audio API graph of a web page in real time.

## Synths
- [Websynths](http://websynths.com/) - Web synthesizer by Mitch Wells.
- [JS Dynamic Audio Synth](http://www.keithwhor.com/music/) - A musical keyboard by Keith William Horwood.
- [106.js](http://resistorsings.com/106/) - Emulation of the classic Roland Juno-106 analog synthesizer.
- [Midi synth](http://webaudiodemos.appspot.com/midi-synth/) - Analog synthesizer simulation loosely based on the architecture of a Moog Prodigy synthesizer.
- [X Sound](https://korilakkuma.github.io/X-Sound/) - Web Synthesizer by [XSound](https://github.com/Korilakkuma/XSound).
- [Acid Machine 2](http://www.errozero.co.uk/acid-machine/) - similar to Propellerhead ReBirth RB-338 (although doesn't claim to be a port)
- [Mod-synth](http://mod-synth.io) - A visual synthesizer with several components and presets. It can also be used with a MIDI controller.

## Drum machines
- [BeatMachine](https://beatmachin.net/)<sup>[*](#disclosure)</sup> - A drummachine with sequencer, midi support and a ddpserver for collaboration.
- [Drums](https://mikedotalmond.github.io/drums/) - A 16-step, 8-track, drum sequencer with per-step sample controls.

## Fun and interesting projects
- [Chrome music lab](https://musiclab.chromeexperiments.com/) - Web Audio experiments aimed at making learning music more accessible to everyone.
- [Plink](http://dinahmoelabs.com/_plink/) - Multiplayer music experience.
- [Modulator](https://lcrespom.github.io/synth/) - An editable graphical node synth.
- [Recreating the ring modulator with web audio](http://webaudio.prototyping.bbc.co.uk/ring-modulator/) - An article on coding the device used to create the voices of the Daleks and the Cybermen in Dr. Who.
- [Pedals.io](https://pedals.io/) - Guitar pedal effects simulation.
- [Wavepot](http://wavepot.com/) - A live digital signal processor (DSP) editor built with web audio.
- [Tweet FM](https://tweet-fm.herokuapp.com/) - An interesting multimedia experiment combining Tweeter feeds and web audio in real time. 
- [The Rick Astley Remix](http://dinahmoelabs.com/rickastley) - Remix Rick Astley's most famous song into different styles.
- [Theremin](https://femurdesign.com/theremin/) - Another Theremin with delays, feedbacks and scuzz.
- [Musical Chord Progression Arpeggiator](http://codepen.io/jakealbaugh/full/qNrZyw/) - An app for creating arpeggios with different progressions and styles.
- [D3 synth](http://roadtolarissa.com/synth/) - A D3 visualization that allows editing a sound loop.
- [Winamp2-js](https://jordaneldredge.com/projects/winamp2-js/) - A reimplementation of Winamp 2.9 using the Web Audio API. [GitHub](https://github.com/captbaritone/winamp2-js)
- [Web audio modem](https://martinmelhus.com/web-audio-modem/) - A project showing how to encode and decode data using the web audio API
- [Music mouse](https://teropa.info/musicmouse/) - A partial emulation by Tero Parviainen of Laurie Spiegel's "Music Mouse - An Intelligent Instrument".
- [AudioNodes](https://audionodes.com/) - Modular audio production suite with multi-track audio mixing, audio effects, parameter automation, MIDI editing, synthesis, cloud production, and more ([download](https://audionodes.com/download), [online version](https://audionodes.com/online))
- [Psyren Audio / Visual Synthesizer](http://www.bolasol.com/psyren/) - interactively generate psytrance squelches ([github](https://github.com/kbola/psyren))

## Performers
- [Live:JS](https://livejs.network/) - A collective of audio and visual artists who build live experiences, shows and installations

## Other web audio lists and resources
- [Chromium Web Audio API Demos](https://chromium.googlecode.com/svn/trunk/samples/audio/samples.html) - Web audio app list curated by the Chromium project members.
- [Web Audio Samples](https://googlechromelabs.github.io/web-audio-samples/) - A collection of projects, examples and resources for Web Audio API. Curated by Chrome Web Audio team.
- [Web Audio Weekly by Chris Lowis](http://tinyletter.com/webaudioweekly) - A weekly newsletter with hints, tips, links and news related to the Web Audio world.
- [Audiocrawl](http://audiocrawl.co/) - A showcase of web audio projects with the possibility of signing up for a monthly newsletter.
- [Awesome Web Audio](https://github.com/notthetup/awesome-webaudio) - A curated list of Web Audio packages and demos.
- [Web Audio/MIDI Demo List](http://webaudio.github.io/demo-list/) - A list kept by the W3C audio working group.
- [10 Virtual Instruments on Browser](http://www.hongkiat.com/blog/virtual-instrument-web-browser/) - 10 Virtual Instruments You Can Play In Your Web Browser.
- [Output Channel](http://outputchannel.com) - A blog featuring Web Audio tutorials and demos/reviews.
- [Awesome audio visualization](https://github.com/willianjusten/awesome-audio-visualization) - A list focusing on visualization but also including general web audio libraries, projects, videos and influential people to follow.
- [Some of the Best Music Pens on CodePen](https://blog.codepen.io/2017/03/17/best-music-pens-codepen/) - A list that includes the best audio-related projects in CodePen.

<a name="disclosure">*</a>: Full disclosure: I am the author of these items.
