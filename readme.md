[//]: # (header-start)

<h1 align="center">
	<a href="https://blog.axway.com/mobile-apps/changes-to-application-development-services">
		Preparing for end of Axway
	</a>	
</h1>
<h2 align="center">
	👇 &nbsp; support for Amplify Cloud and Mobile   &nbsp; 👇
</h2>	

<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		<img src="https://cdn.secure-api.org/images/RIP-Axway-Amplify-Titanium.png" alt="RIP Axway Amplify Titanium (2010 - 2022)" width="80%" />
	</p>
</a>	
<p align="center">
	<a href="https://blog.axway.com/mobile-apps/changes-to-application-development-services">
			🪦 &nbsp; RIP Axway Amplify Titanium (2010 - 2022)
	</a>
</p>
<p align="center">
	<a href="https://blog.axway.com/mobile-apps/prepare-your-apps-for-appcelerator-end-of-support">
			🪦 &nbsp; RIP Axway Amplify Cloud Services (2012 - 2022)
	</a>
</p>
<p align="center">
	<a href="https://blog.axway.com/mobile-apps/prepare-your-apps-for-appcelerator-end-of-support">
			🪦 &nbsp; RIP Axway Amplify Crash Analytics (2015 - 2022)
	</a>
</p>

<hr>
<h4 align="center">
🛑 &nbsp;&nbsp; <a href="https://blog.axway.com/mobile-apps/prepare-your-apps-for-appcelerator-end-of-support">Axway support for Amplify products has ended</a> for most products related to mobile and cloud. 
</h4>

<h4 align="center">
A few of the open-source versions of Axway Amplify products will live on after <a href="">Axway Amplify End-of-Life</a> (EOL) announcements.  However, all closed-source projects and most open-source projects are now dead.  
	</h4>

<p>&nbsp;</p>

> 👉 &nbsp;&nbsp; A group of Axway employees, ex-Axway employees, and some developers from Titanium community have created a legal org and now officially decide all matters related to future of these products.  

<p>&nbsp;</p>
<hr>


## API FAQ:

* [API Best Practices](https://brenton.house)
* [What is API Security?](https://brenton.house/what-is-api-security-5ca8117d4911)
* [OWASP Top 10 List for API Security](https://www.youtube.com/watch?v=GLVHDj0Cpg4)
* [What is API Security?](https://brenton.house/what-is-api-security-5ca8117d4911)
* [Top API Trends for 2022](https://brenton.house/top-10-api-integration-trends-for-2022-49b05f2ef299)
* [What is a Frankenstein API?](https://brenton.house/what-is-a-frankenstein-api-4d6e59fca6)
* [What is a Zombie API?](https://brenton.house/what-is-a-zombie-api-6e5427c39b6a)
* [API Developer Experience](https://brenton.house/keys-to-winning-with-an-awesome-api-developer-experience-62dd2fa668f4)
* [API Cybersecurity 101](https://brenton.house/what-is-api-security-5ca8117d4911)
* [YouTube API Videos](https://youtube.com/brentonhouse)
* [YouTube API Shorts Videos](https://youtube.com/apishorts)

&nbsp;

[![Click to watch on Youtube](https://img.youtube.com/vi/GLVHDj0Cpg4/0.jpg)](https://www.youtube.com/watch?v=GLVHDj0Cpg4&list=PLsy9MwYlG1pew6sktCAIFD5tbrXy9HUQ7  "Click to watch on YouTube")


> &nbsp; [↑ Watch video on YouTube ↑](https://www.youtube.com/watch?v=GLVHDj0Cpg4&list=PLsy9MwYlG1pew6sktCAIFD5tbrXy9HUQ7)

&nbsp;



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
