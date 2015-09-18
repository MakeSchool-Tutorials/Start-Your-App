---
title: "Starting on your own App!"
slug: starting-own-app
---

Not it's time to get started on your own App! 

If you want to use the libraries we used throughout the Makestagram tutorial, you should start a new Xcode project and use Cocoapods (discussed in the second part of the Makestagram tutorial) to install the libraries that we use throughout the tutorials.

If you want to install all dependencies, your `Podfile` should look like this:

	platform :ios, '8.0'
	
	use_frameworks!
	
	pod 'Parse'
	pod 'ParseUI'
	pod 'FBSDKCoreKit'
	pod 'ParseFacebookUtilsV4'
	pod 'ConvenienceKit'
	pod 'Bond'

After you've configured your `Podfile` and ran `pod install` you should be good to go!
