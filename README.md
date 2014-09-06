#Cordova App Development Setup

Introduction/tutorial on how to set up cordova for both Android and IOS development enviroments on a mac machine and android on a windows machiine. (http://docs.phonegap.com/en/edge/guide_platforms_index.md.html#Platform%20Guides)

##Installation 

Make sure to have Node.js installed:
(http://nodejs.org/)

Check in DOS or whatever command line tool you are using
(--version)

So mine is - v0.10.29

===

Make sure to have Apache-Ant Installed:
(http://ant.apache.org/)

Also make sure to delcare this in your enviroment variable/path.

Check the version in command line
(ant -version)

So mine is version 1.9.4 

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

Setup your paths to both the android SDK tools & platform-tools on both Windows/OS X. You may also need to enable Java.

### Android SDK

1. Initial setup for the Android based apps require Eclipse to be installed and for all relevant tool sets to be updated and installed from the Android SDK Manager. 

2. I recommened following the Android SDK setup through their website or through a tutorial. This is only required on first time setup so everything can then be done through Cordova command line. 

3. Create a workspace for your apps through Eciplse.


## Default App Template Setup

This is a basic run through to have a default cordova app for the moment. 

So go to your main development directly in your command line tool.

### Cordova Create
- The first arguement helloworld is the app folder to be generated. Make sure this folder does not already exsit.

 - The second arguement is a revserce domain identfiter

 - The third argument is the apps display title.

 - The second and third arguments can be changed later through the config.xml.

1. cordova create helloworld com.example.hello HelloWorld 

### Add Platforms

You have a few platforms to chose from however this command will only work if each has its SDK or development enviroment setup.

 2. cd helloworld
 3. cordova platform add ios
 4. cordova platform add android
 5. platform ls

 Always run platform ls to check the platforms have installed properly. 

 ### Build the App

 




