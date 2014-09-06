#Cordova App Development Setup

Introduction/tutorial on how to set up cordova for both Android and IOS development enviroments on a mac machine and android on a windows machiine. 

##Installation 

Make sure to have Node.js installed:
(http://nodejs.org/)

Check in DOS or whatever command line tool you are using
(--version)

So mine is - v0.10.29

===
To use Cordova's cross-platform Command Line Interface/CLI:

* on OS X:
	$ sudo npm install -g cordova

* on Windows:
	C:\>npm install -g cordova

The -g tag will install cordova globally/on the entire machine rather than in the node_modules subdirectory of the current working directly. 

===

## Installation Android

Download the Android SDK:

* For both OS X & Windows:
	(http://developer.android.com/sdk/index.html)

* Windows:
Create a Development folder in your Users directly, so for example this is where mine is - "C:\Users\Ivy\Development" Or anywhere you want to.

then unzip your Android SDK file into the Development directly.

* OS X:
You can either repeat the windows step or Create a seperate Android folder for the SDK. Make sure to make a development folder, you do not want to have all of your app code bundled up in your main work folder. 

* Environment Variables:

Setup your paths to both the android SDK tools & platform-tools on both Windows/OS X. 
