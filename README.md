# Android Research: What are there for us to know more about Android apps :)
In this repository, I will share interesting research studies, tools, etc., related to Information flow analysis in Android applications.
## How do you search within the Android Source code repository?
Here is a [search engine](https://cs.android.com/) that allows one to search for codes within the Android source code repo.
## How do you retrieve Android application apk files?
There are different ways to get access to apk files of Android apps:
1. By using an API available at this [github repository](https://github.com/egirault/googleplay-api).
2. By inserting the package or Google Play URL at [this link](https://apps.evozi.com/apk-downloader), the downloadable apk will appear.
3. By looking for the application package or name on [APKpure website](http://apkpure.com). 
### Interesting Open-source Android app list
+[Awesome apps](https://github.com/timschneeb/awesome-shizuku?tab=readme-ov-file#audio)
+[Open source Android apps](https://github.com/pcqpcq/open-source-android-apps/tree/master)
+[Amazing Android apps](https://github.com/Mybridge/amazing-android-apps?tab=readme-ov-file)
+[HackDroid](https://github.com/thehackingsage/hackdroid?tab=readme-ov-file)
+[Awesome Android Kotlin Apps](https://github.com/androiddevnotes/awesome-android-kotlin-apps)
##Information leakage in Android 
### Android API Levels
[Android API Levels and their popularity distribution](https://apilevels.com/)
### Taint-Analysis
This is a good [link](https://dzone.com/articles/what-is-taint-analysis-and-why-should-i-care) that describes taint-analysis and sanitization.

###Side Channels in Android
1. It is possible to infer what a user is typing by listening to the audio made when he/she is typing on the keyboard, according to a [study](https://techxplore.com/news/2019-06-smartphone-finger-side-channel.html).
