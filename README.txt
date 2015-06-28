#  Extends Modernizr to detect video autoplay functionality

Builds on this codepen: http://codepen.io/davidgenetic/pen/FmHaD
- David's codepen detects HTML5 Audio element autoplay functionality

Uses video data from this gist: https://github.com/kud/blank-video

Main purpose of this detection is to determine whether a given device will permit the video autoplay functionality. Many handheld devices block this functionality, requiring a user interaction (for instance a screen tap) before playing videos.

Pen also includes (currently not working) test code to see if a device forces videos to play fullscreen.

__Tests are asynchronous!__ Results are not immediately available.
