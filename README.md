# XamarinMultiDex
Sample of how to set up multidex using support library and binding project for Android pre lollipop 

To use compile and reference the AndroidMultiDex library. This project creates a binding for the Android MultiDex Support Library.

After the project has been referenced modify the applicaiton's manifest to add the android:name attribute to derive your application from the Android MultiDex Support Library. For example:

`<?xml version="1.0" encoding="utf-8"?>`<br>
`<manifest xmlns:android="http://schemas.android.com/apk/res/android" package="AndroidMultiDexTest.AndroidMultiDexTest" android:versionCode="1" android:versionName="1.0">`<br>
` <uses-sdk android:minSdkVersion="16" />`<br>
`	<application android:label="AndroidMultiDexTest"`<br>
`        android:name="android.support.multidex.MultiDexApplication">`<br>
`    </application>`<br>
`</manifest>`
