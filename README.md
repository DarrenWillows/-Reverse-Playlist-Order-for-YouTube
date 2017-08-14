# Reverse Playlist Order for YouTube

To use it you will need a userscript manager, like Tampermonkey or Greasemonkey.

Creates a button on your playlists which allows you to reverse the order of the videos.
Based on the Standalone YouTube Plus Reverse Playlist that is now dead.

I created 1.0.3a as 1.0.3 has stopped working on Firefox and is no longer supported by the creator.

###Download

Userscript: 
[ReverseYouTubePlaylist.js][ReverseYouTubePlaylist.js]
[ReverseYouTubePlaylist.js]: https://github.com/DarrenWillows/-Reverse-Playlist-Order-for-YouTube/raw/master/ReverseYouTubePlaylist.js

[prev]: https://cloud.githubusercontent.com/assets/9222661/6228114/67b6385c-b697-11e4-8e5b-c6e6f9c0ab71.png "Reverse Prev"

==UserScript==

@version     1.0.3a

@name        Reverse Playlist Order for YouTube

@namespace   https://github.com/ParticleCore

@description Reverse the order of YouTube playlists

@match       *://www.youtube.com/*

@run-at      document-start

@downloadURL https://github.com/ParticleCore/Particle/raw/master/MDL/rpo.user.js

@grant       none

@noframes
