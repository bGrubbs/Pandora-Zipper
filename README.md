Pandora-Zipper
==============

add meta tags to 28 songs from Pandora to zip download to your PC.

###How does it work?
Pandora Zipper is a PHP application that allows you to download songs that have been loaded using pandora's unofficial API.
The program first collects 28 song urls by cycling through the 6 skip limit that pandora has. This is done through an http request that recieves
4 songs per skip. (first 4 + 6*4 skips = 28)

The application then processes the information using php reader and applies metatags in both ID3 and ilst formats through PHP Reader. Once metadata
has been added, it is zipped and sent back to the browser for download.

Want to see the above written in shitty code? [Here's the git repo.](https://github.com/bGrubbs/Pandora-Zipper/)

###Privacy Policy
Pandora.com is the legal owner and distributor of the songs that we allow you to download for strictly personal use.

We do not support or encourage the distribution or use of the music generated by this software for purposes other than personal endeavors. This includes commerce.

We allow third-party companies, namely google analytics, collect certain anonymous information when you visit our web site.

These companies may use non-personally identifiable information (e.g., click stream information, browser type, time and date, subject of advertisements clicked or scrolled over)
during your visits to help us optimize and maintain our site. These companies typically use a cookie or third party web beacons to collect this information.
To learn more about this behavioral advertising practice or to opt-out of this type of advertising, check out (http://www.google.com/policies/technologies/ads/)[how Google Analytics advertises.]
###DMCA
If you feel that the distribution of music available here have infringed on your rights or copyrights, please send an email to flamurds@gmail.com
together with your credentials and a brief reason for your claim. Our support team will respond promptly. Thank you.