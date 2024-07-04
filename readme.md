# NVGT Player
A simple example sound player for [NVGT](https://nvgt.gg).

Written by [braillescreen](https://github.com/braillescreen)

Modified by [ironcross32](https://github.com/ironcross32)

### Introduction

NVGTPlayer is an easy-to-use URL streamer. You can load any valid URl to a direct stream, and these streams show up in a list with names you give them. They are saved on exit and retrieved on startup.

### Usage

When the application is started for the first time, the list of streams will be empty. To fix this, tab to the, "Open new URL" button and activate it with space or enter. Next, type or paste in the URL you'd like to play. A few seconds will pass in which the application will attempt to load the URL. At this point, if the loading is successful, you will be asked for a name. This name will appear in the list, so choose carefully. Once the name is given, the stream will begin playing.

Continuing to tab through the interface, there is a keyboard area that accepts inputs.
* Up and down arrows adjusts the volume
* Space bar pauses and resumes playback
* Escape exits the application

The, "Open URL from list", button will load the url associated with the currently selected name in the list.

The, "Select output device", list and it's associated button will switch the destination of playback to the selected device. This is useful for playing the stream through speakers or a virtual audio cable without affecting the system default device.