# gtm2-youtube-event-tracking

This Javascript file encased in `<script>` tags allows someone who is not a developer to "attach" the
script to html pages that have been enabled with Google Tag Manager. The following YouTube events are
then generated: ENDED, PLAYING, PAUSED, BUFFERING, CUED. The events can then be analysed in Google Analytics.

This code is based on Lunametrics code (attribution see below). However this code only spits out the events
listed above and is only concerned with the newer form of YouTube embedded videos. But here I have added
requests to Google's YouTube API to get the video title that corresponds to the video id which is part of
the YouTube url that is embedded in a html page.

For detailed instructions on how to use this code with Google Tag Manager and Google Analytics see [grantmarch.github.io/gtm2-youtube-event-tracking](http://grantmarch.github.io/gtm2-youtube-event-tracking)

## References

This code is adapted from code written by [Sayf Sharif](https://twitter.com/sayfsharif) and [Dan Wilkerson](https://twitter.com/notdanwilkerson)  of [Lunametrics](http://www.lunametrics.com) [Github](http://www.lunametrics.com/blog/2015/05/11/updated-youtube-tracking-google-analytics-gtm) [Explanation](http://www.lunametrics.com/blog/2015/05/11/updated-youtube-tracking-google-analytics-gtm) 

[Google Developers: New and old format of YouTube embedded videos](https://developers.google.com/youtube/player_parameters?hl=en)

[Google Developers: YouTube Player API Reference for iframe Embeds](https://developers.google.com/youtube/iframe_api_reference)

[Google Developers: YouTube Data API](https://developers.google.com/youtube/v3/getting-started)

