<img id="app" src="images/app.png"/>

# MarkNote, the Android markdown note-taking application

> MarkNote is a markdown note-taking application for Android. It has many cool features which can fit most of the requirements of the user. Now it is open sourced on Github for communication and studying. Surely, we hope that you can join the development of MarkNote to make it more useful.

## 1. About MarkNote

<img src="images/mark.png" align="left" width="160" hspace="10" vspace="10"/>

MarkNote is an open sourced Markdown note-taking applicatioin with the material deigsn styled UI. **The application now has many cool features, including MathJax, basic makdown grammers etc.** The application can now fit most of the requirements of the user. The main purpose of making it open source is for communication and studying. And at the same time, we hope that you can join the developement of MarkNote to make it more helpful.

You can join our [Google+ community](https://plus.google.com/u/1/communities/102252970668657211916), follow the development state and join the beta test.

MarkNote is now published to the [CoolApk market](https://www.coolapk.com/apk/178276), which is a popular App store in China. And I will upload it to Google Store in few days. I welcome that you download it, use it and feedback for it. **The app now support three kinds of languages including Simplified Chinese, Traditional Chinese and English.** So feel free to use it!

By the way, I have just developed another app [OmniList](https://www.coolapk.com/apk/185660) and open sourced at [Github](https://github.com/Shouheng88/OmniList), witch is used to manage your daily time. 

## 2. Introduction

<a href="#app">Here</a> is some screenshots of this app used to show the features and current development state. Next, I will tell you some details about its functions and the development skills included. 

<div style="display:flex;" >
<img  src="images/1.png" width="19%" >
<img style="margin-left:10px;" src="images/2.png" width="19%" >
<img style="margin-left:10px;" src="images/3.png" width="19%" >
<img style="margin-left:10px;" src="images/4.png" width="19%" >
<img style="margin-left:10px;" src="images/5.png" width="19%" >
</div>

## 3. Functions and features

Here I made a list of its functions:

|No.|Functions|
|:-:|:-:|
|1|Basic **ADD, UPDATE, ARCHIVE, TRASH, DELETE** options|
|2|Basic markdown grammers including some advanced features like **MathJax** |
|3|The beautiful **TIMELINE** to collect your actions in app (**LOCAL ONLY**)|
|4|Multi-media, including **FILES, VIDEOS, AUDIOS, PICTURES, PAINTING and LOCATIONS** etc|
|5|**MULTI-THEMES**, support **DAY-NIGHT MODE** and many other colorful **THEMES**|
|6|Colorful **CHARTS** to show your statistics|
|7|Three different kinds of **APP WIDGET** and you can add short cut for every note|
|8|You can add beautiful tags for your note|
|9|Manage your notes in “file tree” and your can easily search your articles|
|10|Support **EXPORT TO PDF, TXT, MD, HTML and IMAGES**|
|11|App independent **LOCK** to protect your notes|
|12|Backup to **ONEDRIVE** and internal storage|
|13|**COMPRESS** image to save your storage|

The functions considered to include in future:

|No.|Functions|
|:-:|:-:|
|1|Backup to more platforms and keep the file names|
|2|Use cloud storage to store files and images, use link in note only|
|3|Real-time markdown preview|
|4|Allow to edit the check box in note|
|5|Use map to display the locations|
|6|Change and refine the structure of note|

You can get the latest release notes at [change log](app/src/main/res/raw/changelog.xml).

## 5. Dependencies

MarkNote used DataBinding and some other skill as listed below. Thanks to there greate work!

|No.|Dependency|Description|
|:-:|:-:|:-:|
|1|[arch.lifecycle]()||
|2|[Stetho](https://github.com/facebook/stetho)|Facebook debug tools|
|3|[Fabric]()|Error tracking|
|4|[RxBinding](https://github.com/JakeWharton/RxBinding)||
|5|[RxJava](https://github.com/ReactiveX/RxJava)||
|6|[RxAndroid](https://github.com/ReactiveX/RxAndroid)||
|7|[OkHttp](https://github.com/square/okhttp)||
|8|[Retrofit](https://github.com/square/retrofit)||
|9|[Glide](https://github.com/bumptech/glide)||
|10|[BRVAH](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)|Useful RecyclerView adapter|
|11|[Gson](https://github.com/google/gson)||
|12|[Joda-Time](https://github.com/JodaOrg/joda-time)|Java time library|
|13|[Apache IO](http://commons.apache.org/io/)|File library|
|14|[Material dialogs](https://github.com/afollestad/material-dialogs)||
|15|[PhotoView](https://github.com/chrisbanes/PhotoView)||
|16|[Hello charts](https://github.com/lecho/hellocharts-android)||
|17|[FloatingActionButton](https://github.com/Clans/FloatingActionButton)||
|18|[HoloColorPicker](https://github.com/LarsWerkman/HoloColorPicker)||
|19|[CircleImageView](https://github.com/hdodenhof/CircleImageView)||
|20|[Changeloglib](https://github.com/gabrielemariotti/changeloglib)||
|21|[PinLockView](https://github.com/aritraroy/PinLockView)|App Lock|
|22|[BottomSheet](https://github.com/Kennyc1012/BottomSheet)|Bottom dialog|
|23|[Luban](https://github.com/Curzibn/Luban)|Image compress|
|24|[Flexmark](https://github.com/vsch/flexmark-java)|Markdown parser for Java|
|25|[PrettyTime](https://github.com/ocpsoft/prettytime)|Beautify the time text|

### Markdown Parser

You can use javascript and parse markdown text in webview, or use java to parse and display it in webview as we did. I think the later is better, because we Android developers are more farmily with Java. In this app, we used the FlexMark to parse the mardkown text.

## 5. Particpate

As mentioned above, MarkNote still has many weaknesses. If you are interested in contributing to it, for the project and make a pull request. Also, you can follow the development state at [waffle.io](https://waffle.io/Shouheng88/NotePal). If you find some unpleasent bugs, please don't be heasitated to report to me by [Email](mailto:shouheng2015@gmail.com).

## 6. Feedback

If you have any good idea about this app, please contact me at [shouheng2015@gmail.com](mailto:shouheng2015@gmail.com). 
