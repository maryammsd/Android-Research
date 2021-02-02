# Android-Analysis
In this repository, I am going to share the interesting research studies, tools, etc. related to Information flow analysis in Android applications.
## How to search within Android Source code repository?
Here is a [search engine](https://cs.android.com/) that one can search for codes within android source code repo.
## How to retrieve Android application apk files?
There are different ways to get access to apk files of Android apps:
1. By using an API availabale at this [github repository](https://github.com/egirault/googleplay-api) .
2. By inserting the package or Google Play URL at [this link](https://apps.evozi.com/apk-downloader), the downloadable apk will appear .
3. By looking for the applicatin package or name in [APKpure website](http://apkpure.com). 

##Information leakage in Android 
### Information Flow

### Taint-Analysis
Here is a good [link](https://dzone.com/articles/what-is-taint-analysis-and-why-should-i-care) that describes taint-analysis and sanitization.

###Side Channels in Android
1. It is possible to infer what is a user typing by listening to the audio made when he/she is typing on the keyboard according to a [study](https://techxplore.com/news/2019-06-smartphone-finger-side-channel.html).
