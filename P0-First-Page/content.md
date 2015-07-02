---
title: "Starting on your own App!"
slug: starting-own-app
---

Not it's time to get started on your own App! 

##Starting with our template project

If you want to use the same frameworks (Parse, Facebook SDK, etc.) that you have used throughout our tutorials, you can get started by downloading this [template project](https://github.com/MakeSchool/Makestagram-Swift-Solution/archive/TemplateProject.zip).

##Installing dependencies via CocoaPods

If you prefer, you can start with a blank Xcode project. You can then use CocoaPods (discussed in the second part of the Makestagram tutorial) to install the libraries that we use throughout the tutorials.

If you want to install all dependencies, your `Podfile` should look like this:

	platform :ios, '8.0'
	
	use_frameworks!
	
	pod 'Parse'
	pod 'ParseUI'
	pod 'FBSDKCoreKit'
	pod 'ParseFacebookUtilsV4'
	pod 'ConvenienceKit'
	pod 'Bond'