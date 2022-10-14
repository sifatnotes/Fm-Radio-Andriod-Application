# Fm-Radio-Andriod-Application
FM Radio Andriod Source Code Full Source Code With Documentation
Table of Contents
Which Android Studio version is needed?
How to open the project in Android Studio?
How to change the package name?
How to change app name?
How to change Fm Url
How to change Facebook and Twitter url
How to change FM Detail
How to change AboutUs
How to change Privarcy Policy
How to enable/disable RTL?
How to change AdMob id?
How to change 'Splash Screen, Application Icon and MoreApp link'?
How to Change One Signal Notification App Id in Application?
Graphics
App Showcase
Rating
Credits

Which Android Studio version is needed?
Latest Android Studio version is recommended, which can be downloaded from here:
http://developer.android.com/intl/es/sdk/index.html





How to open the project in Android Studio?
Open Android Studio > Open an Existing Android Studio Project > Select Your Project build.gradle file > ok
Select Project




How to change the package name?
You can change it easily from Android Studio. Here are the steps: You can change it easily from Android Studio. Here are the steps:

In the Project pane, click on the little gear icon.Uncheck/Deselect the Compact Empty Middle Packages option.
Your package directory will now be broken up in individual directories.
Individually select each directory you want to rename, and: Right-click itSelect RefactorClick on RenameIn the Pop-up dialog.
Click on Rename Package instead of Rename Directory Enter the new name and hit RefactorAllow a minute to let Android Studio update all changes.
Now open your build.gradle (Usually 'app' or 'mobile'). Update the applicationId to your Package Name and Sync Gradle, if it hasn't already been updated automatically.

Note: When renaming com in Android Studio, it might give a warning. In such case, selectRename All.












How to change app name?
Open Android Studio >MyFm> res > values > strings.xml
Enter your app name inside "app_name" string tag:
<string name="app_name">MyFm</string>


How to change Fm Url

Replace the your Fm url string.xml file
Open Android Studio >MyFm> res > values > strings.xml
Enter your Fm url inside "fmUrl" string tag:
<string name="fmUrl">Your Fm Url</string>



How to change Facebook and Twitter url

Replace the your Facebook and Twitter url string.xml file
Open Android Studio >MyFm> res > values > strings.xml
Enter your Facebook and Twitter url inside "facebookLink" and "twitterLink" string tag:
<string name="facebookLink">Your Facebook Url</string>
<string name="twitterLink">Your Twitter Url</string>



How to change Fm Detail

edit your FM detail




How to change AboutUs

edit your about us




How to change Privarcy Policy

edit your Privarcy Policy




How to enable/disable RTL?
Open Android Studio > app > res > values > strings.xml
Change isRTL to true if you want to enable or fase if you want to disable
Change all the text below in your language


How to change AdMob id?
Open Android Studio > MyFm > res > values > strings.xml
Enter your AdMob Banner id inside "admob_banner_id" string tag:
<string name="admob_banner_id">Your AdMob Bannner ID Here</string>
Enter your AdMob intertestial id inside "admob_interstitial_id" string tag:
<string name="admob_interstitial_id">Your AdMob Intertestial ID Here</string>





How to change 'Splash Screen, Application Icon and MoreApp link'?
How To Change Application Icon

Open Android Studio > app > res > drawable-mdpi,drawable-xhdpi and drawable-xxhdpi > icon.png
Rename your icon with icon.png and paste in drawable-mdpi,drawable-xhdpi and drawable-xxhdpi folder


How To Change Splash Screen
Open Android Studio > app > res > drawable > splash.png
Rename your splash screen image with splash.png and paste in drawable folder
How To Change MoreApp Link

Open Android Studio > app > res >values > strings.xml
Enter your Play Store Apps Link inside "play_more_apps" string tag:
<string name="play_more_apps">https://play.google.com/store/search?q=movie;<string/>



How to Change One Signal Notification App Id in Application?
Get your Google Server API key and project number.
https://documentation.onesignal.com/docs/generate-a-google-server-api-key

How to Change One Signal App Id And Sender Id

Open Android Studio > App > build.gradle(Module:app)
Enter your Onesignal App id inside"onesignal_app_id"
onesignal_app_id ="Your onesignal_app_id"



Change App all graphics
You will find all image into /res/drawable-mdpi/,/res/drawable-hdpi/,/res/drawable-xhdpi/ folder. Just create your own graphics and replace those files. Create seperate graphics of different device screen sizes & place them into other drawble folders (drawable-hdpi & drawable-xhdpi) with same file name found at drawable-mdpi folder. Check here for more information: Devices and Displays & Supporting Multiple Screens.





Application Showcase in PlayStore
Once you will publish your app to Google Play or any other Android store, send us your app link. We will happy to showcase your app into our website & CodeCanyon page.


Rating
If you like our app, we will highly appreciate if you can provide us a rating of 5. You can rate us from your CodeCanyon Menu > Download page.


Credits
I've used folowing sources into this app:

Admob
OneSignal
Android ViewPagers Transformers
Om Recorder
RadioPlayerService
