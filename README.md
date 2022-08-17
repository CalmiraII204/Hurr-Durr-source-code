## Hurr-Durr-source-code
- I always wanted to make a funny site like Hurr-Durr, so, I got some info about hurr-durr in the [WayBackMachine](http://web.archive.org), I also saw [this repository](https://github.com/Mydoge/hurr-durr), and looked at the source code of hurr-durr.cc.
- Now if you wanted to make one like this, ehh, just fork it. **(i dont care lmao)**

## About Hurr-Durr (this is taken from [The Malware Wiki](https://malwiki.org/index.php?title=Hurr-Durr))
Hurr-Durr was a joke website with a fan-made trojan (executable) which infected Microsoft Windows by exploiting browser vulnerabilities. It worked with Internet Explorer, Firefox, and Chrome. It did not harm the user's computer (with the exception of the fan-made trojan), but it could get annoying. As of 2017, the website no longer works. However, you can visit the archived version from Web Archive.

## Payload (this is taken from the malware wiki too)
When the website was opened, an animated image of a dancing bulldog is displayed and the site plays an audio file of a song called "Chacarron Macarron". Once the Javascript payload fully loads, the browser window begins to move randomly. This functionality only works on older versions of Internet Explorer and may not work on other browsers. Whenever a user attempts to close the tab or window, it generates a dialogue box, which prevents the browser from being closed. This is very similar to the "You Are An Idiot" virus, being that it doesn't harm the system, instead merely aggravating the user.

Since the site does not block Task Manager or alternative closing methods (such as using Alt-F4 or taskkill,) it is easy to close the browser by using Task Manager, unlike "You Are An Idiot".

Hurr-Durr's payload may not work on browsers other than older versions of Internet Explorer; if the user attempts to visit the website on Microsoft Edge, attempting to close the tab or the window will result in a hang, so if other tabs are open, the tab will freeze for about 5 seconds, then it will close; on Firefox, the window will entirely hang, and the only way to stop this is to end Firefox's task in Task Manager.
