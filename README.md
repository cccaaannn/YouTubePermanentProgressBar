# YouTube Permanent ProgressBar
#### Keeps YouTube progress bar visible all the time.
___

![GitHub top language](https://img.shields.io/github/languages/top/cccaaannn/YouTubePermanentProgressBar?style=flat-square) [![Greasy Fork](https://img.shields.io/greasyfork/l/426283?style=flat-square&color=green)](https://greasyfork.org/en/scripts/426283-youtube-permanent-progressbar) [![Greasy Fork](https://img.shields.io/greasyfork/v/426283?style=flat-square&color=blueviolet)](https://greasyfork.org/en/scripts/426283-youtube-permanent-progressbar) [![Greasy Fork](https://img.shields.io/greasyfork/dt/426283?style=flat-square&color=blue)](https://greasyfork.org/en/scripts/426283-youtube-permanent-progressbar) [![Greasy Fork](https://img.shields.io/greasyfork/rating-count/426283?style=flat-square&color=teal)](https://greasyfork.org/en/scripts/426283-youtube-permanent-progressbar)


**Install script from [greasyfork youtube-permanent-progressbar](https://greasyfork.org/en/scripts/426283-youtube-permanent-progressbar)**


### Features
- No additional css required.
- Works with new (chaptered) videos.

### Options
You can change some options from the script.
- Update interval.
- Progress bar opacity separately for full screen and window modes.


```javascript
options : {
    UPDATE_INTERVAL : 500,                   // Update interval in milliseconds, decrease for smoother progress movement or increase for performance.
    PROGRESSBAR_OPACITY_WINDOW : 1,          // Progress bar opacity on window mode between 0 - 1.
    PROGRESSBAR_OPACITY_FULLSCREEN: 0.5,     // Progress bar opacity on fullscreen mode between 0 - 1.

    UPDATE_VIDEO_TIMER : true,
    UPDATE_PROGRESSBAR : true,
    UPDATE_BUFFERBAR : true
}
```
