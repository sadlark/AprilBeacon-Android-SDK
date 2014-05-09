# AprilBrother-Android-SDK

AprilBrother SDK for Android

## Docs

* [Current JavaDoc documentation](//aprilbrother.github.io/aprilbeacon-android-sdk/JavaDocs/index.html)
* [Community for AprilBeacon](http://bbs.aprbrother.com)

## Installation

* Copy ab-sdk-beta.jar to your libs directory.
* Add following permissions and service declaration to your AndroidManifest.xml:
```
 <uses-permission android:name="android.permission.BLUETOOTH"/>
 <uses-permission android:name="android.permission.BLUETOOTH_ADMIN"/>
 <service android:name="com.aprilbrother.aprilbrothersdk.service.BeaconService"
         android:exported="false"/>
```

## Precautions
* If you want to use change the characteristic you should make sure that our beacon's hardware is above 2.0
* When you change the characteristics you should reset the beacon
