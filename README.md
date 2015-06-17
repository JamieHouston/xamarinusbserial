# Xamarin USB Serial for Android

This is a wrapper and example projects of the usb-serial-for-android for Xamarin. 

usb-serial-for-android is a driver library for communication with Arduinos and other USB serial hardware on Android, using the [Android USB Host API](http://developer.android.com/guide/topics/connectivity/usb/host.html) available on Android 3.1+.

No root access, ADK, or special kernel drivers are required; all drivers are implemented in Java. You get a raw serial port with Read(), Write(), and other basic functions for use with your own protocols.

* **Homepage:** https://bitbucket.org/lusovu/xamarinusbserial
* **NuGet:** https://www.nuget.org/packages/LusoVU.XamarinUsbSerialForAndroid/

## Structure

The solution is composed of two projects:

* UsbSerialForAndroid - A wrapper of the .jar into a managed assembly that can be used in a .NET project.    
	
* UsbSerialExample - A conversion into Xamarin of the example project supplied with usb-serial-for-android.
	
## Author, License, and Copyright

This library is licensed under LGPL Version 3. Please see LICENSE.txt for the complete license.

Copyright 2014, LusoVU. All Rights Reserved.

Portions of this library are based on usb-serial-for-android (https://github.com/mik3y/usb-serial-for-android).