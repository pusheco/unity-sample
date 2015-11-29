# Unity Sample for Pushe

This is a sample application (made by Unity), which is powered by [Pushe](http://pushe.co) push notification service.

You can see other samples:
* [Android Studio](https://github.com/ronashco/pushe-android-studio-sample)
* [Eclipse](https://github.com/ronashco/pushe-eclipse-sample)
* [Basic4Android](https://github.com/ronashco/pushe-b4a-sample)

To see our demo app or its wiki page you may take a look at:
* [Download app from Google Play](https://play.google.com/store/apps/details?id=co.ronash.pushesample)
* [Github Repository](https://github.com/ronashco/pushe-sample)

## Pushe Installation in a Unity Project 

###Import Pushe to project

1. Download [Pushe.unitypackage](http://static.pushe.co/sdk/pushe-0.8.2.unitypackage)
2. Right click on Assets and select import package/custom package and browse downloaded file
3. Drag PusheGameObject prefab from Assets/Source to Hierarchy window

###Change project settings

1. Select Build Settings from File menu
2. select Android platform and click on Player Settings
3. Set Minimum API Level to 16
4. Set your application package name in Bundle Identifier field

###Change AndroidManifest.xml

1. Go to your Pushe panel and add your applicatin with the same application package name selected in Bundle Identifier
2. Download given Manifest file
3. Add CopyToManifest.xml content to your AndroidManifest.xml in Assets/Plugins/Android

   **note:** If your application doesn`t have such a manifest, add tihs content to Pushe manifest in Assets/Plugins/Android/Pushe folder
   
Your project is ready to launch. Select Build&Run from File menu and test it on your device.

## More Info
For detailed documentations visit http://docs.pushe.co


## Support 
#### Email:
support [at] pushe.co
#### Phone:
+98-21-44668276 (8:00 to 17:00 Sat-Thu)
