# gtm2-youtube-event-tracking

This Javascript file encased in `<script>` tags allows someone who is not a developer to "attach" the
script to html pages that have been enabled with Google Tag Manager. The following YouTube events are then generated: ENDED, PLAYING, PAUSED, BUFFERING, CUED. The events can then be analysed in Google Analytics.

This code is based on Lunametrics code (attribution see below), however this code only spits out the events listed above. But here we have added requests to Google's YouTube API to get the video title that corresponds to the video id which is part in YouTube url that is embedded in a html page.

For detailed instructions on how to use this code with Google Tag Manager and Google Analytics see [grantmarch.github.io/gtm2-youtube-event-tracking](http://grantmarch.github.io/gtm2-youtube-event-tracking)

This code is adapted from code written by Dan Wilkerson of [Lunametrics](http://www.lunametrics.com) [Github](http://www.lunametrics.com/blog/2015/05/11/updated-youtube-tracking-google-analytics-gtm) [Explanation](http://www.lunametrics.com/blog/2015/05/11/updated-youtube-tracking-google-analytics-gtm) 
