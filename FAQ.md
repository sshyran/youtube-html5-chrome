## Why is there no full screen option? ##

> The aim of this extension is to highlight the standards based video support in HTML5. The JavaScript API does not provide a direct way to enable full-screen mode due to the possibility of misuse by malicious scripts. Browsers will have to provide this option to the user or allow a way for scripts to request full screen mode. As of now this is not part of the HTML5 spec.

> I am working on a way to enlarge the video within the page, which you could then use F11 to full screen the browser.

## Why is the quality worse than Flash? Why is playback slower? ##

> The way the extension currently works is by streaming the MP4 version of the video from YouTube. From what I understand, this is the same video the Flash player uses, however the video decoding used by the browser may not yet be optimized as well as it can be so you may experience lower quality or slower playback than flash. This should improve in the future as browsers are improved.

## Why does seeking sometimes move to the wrong position? ##

> Everything related to video playback is completely under the control of Chrome itself. My extension merely provides the browser with the proper markup to enable the native support. If you find there are bugs or other problems you may want to inquire on the Chromium development group about the problem.