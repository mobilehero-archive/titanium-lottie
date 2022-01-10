[//]: # (header-start)

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
<h1 align="center">
	Axway Amplify End-of-Life Announcement
</h1>
<h2 align="center">
	👇 &nbsp; See notes below  &nbsp; 👇
</h2>	
</a>

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		<img src="https://cdn.secure-api.org/images/RIP-Axway-Amplify-Titanium.png" alt="RIP Axway Amplify Titanium (2010 - 2022)" width="80%" />
	</p>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		🪦 &nbsp; RIP Axway Amplify Titanium (2010 - 2022)
	</p>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		🪦 &nbsp; RIP Axway Amplify Cloud Services (2012 - 2022)
	</p>
</a>
<hr>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<h4 align="center">
🛑 &nbsp;&nbsp; All products affected by the announcements will not be supported by Axway effective their EOL dates in 2022.
</h4>

<h4 align="center">
Some Open-Source versions of Axway products will live on after End-of-Life (EOL) Axway Amplify product announcements.  However, some products are closed-source and will NOT continue after the shut down in 2022.  
	</h4>
</a>
<p>&nbsp;</p>

> 👉 &nbsp;&nbsp; Stay tuned for more info as plans are being made to save the Titanium project and move it under the control of a independent group of developers.

<p>&nbsp;</p>
<hr>
<p>&nbsp;</p>
<p>&nbsp;</p>

[//]: # (header-end)



# @titanium/lottie

[![@titanium/lottie version](https://img.shields.io/npm/v/@titanium/lottie.png)](https://www.npmjs.com/package/@titanium/lottie)
[![@titanium/lottie downloads](https://img.shields.io/npm/dm/@titanium/lottie.svg)](https://www.npmjs.com/package/@titanium/lottie)
[![@titanium/lottie dependencies](https://img.shields.io/librariesio/release/npm/@titanium/lottie.svg)](https://www.npmjs.com/package/@titanium/lottie)
<br/>

* [📝 Description](#-description)
* [🚀 Getting Started](#-getting-started)
	* [Install `@titanium/lottie` in root of project](#install-titaniumlottie-in-root-of-project)
		* [Create an an animation in controller](#create-an-an-animation-in-controller)
		* [Create an an animation in view](#create-an-an-animation-in-view)
* [✨Features](#features)
* [Library versions:](#library-versions)
* [📚Learn More](#learn-more)
* [📣 Feedback](#-feedback)
* [©️ Legal](#️-legal)


<br/>

## 📝 Description

> Native modules that allows you to use [Airbnb Lottie](https://airbnb.design/lottie/) animations with Axway Titanium native mobile apps.
>    
> This is a repackaging of the compiled iOS and Android modules for [Ti.Animation](https://github.com/m1ga/ti.animation) to allow for installation via npm.

## 🚀 Getting Started

### Install `@titanium/lottie` in root of project

```bash
npm install @titanium/lottie
```


#### Create an an animation in controller

```js
const lottie = require('@titanium/lottie');

const animation = lottie.createAnimationView({
   id: 'lottie_test',
   file: 'lottie_sample.json',
   loop: true,
   autoStart: true,
   height: 500,
   width: Ti.UI.FILL,
});

// add the animation to any window or view
$.index.add(animation);
```

OR

#### Create an an animation in view

```xml
<AnimationView 
   id="lottie_test" 
   module="@titanium/lottie" 
   file="lottie_sample.json" 
   loop="true" 
   autoStart="true" 
   height="500" 
   width="fill" />
```


## ✨Features

* [x] Includes Titanium native iOS module: `ti.animation 2.0.0`
* [x] Includes Titanium native Android module: `ti.animation 4.0.0`
* [x] Display Lottie animations

## Library versions:

The Titanium modules use external libraries

|Library|Platform|Version|Build Date|
|---|---|---|---|
| [Airbnb Lottie](https://github.com/airbnb/lottie-android) | Android | 3.4.0 | 2020/02/22 |
| [Airbnb Lottie](https://github.com/airbnb/lottie-ios) | iOS | 2.5.2 | 2018/12/10 |





## 📚Learn More

⭐  [Ti.Animation GitHub Repo](https://github.com/m1ga/ti.animation) - Repo for Ti.Animations modules    
⭐  [LottieFiles](http://www.lottiefiles.com/) - Free Lottie animations    


## 📣 Feedback

Have an idea or a comment?  [Join in the conversation here](https://github.com/brentonhouse/titanium-lottie/issues)! 

## ©️ Legal

Modules are licensed under Apache 2.0 from https://github.com/appcelerator-modules/titanium-lottie

Alloy is developed by Appcelerator and the community and is Copyright © 2012-Present by Appcelerator, Inc. All Rights Reserved.

Alloy is made available under the Apache Public License, version 2. See their license file for more information.

Appcelerator is a registered trademark of Appcelerator, Inc. Titanium is a registered trademark of Appcelerator, Inc. Please see the LEGAL information about using trademarks, privacy policy, terms of usage and other legal information at http://www.appcelerator.com/legal.
