# @titanium/lottie

[![@titanium/lottie](https://img.shields.io/npm/v/@titanium/lottie.png)](https://www.npmjs.com/package/@titanium/lottie)


> Native modules that allows you to use [Airbnb Lottie](https://airbnb.design/lottie/) animations with Axway Titanium native mobile apps.

- [📝 Description](#-Description)
- [🚀 Getting Started](#-Getting-Started)
	- [Install `@titanium/lottie` in root of project](#Install-titaniumlottie-in-root-of-project)
	- [Create a View](#Create-a-View)
- [✨Features](#Features)
- [Library versions:](#Library-versions)
- [📚Learn More](#Learn-More)
- [📣 Feedback](#-Feedback)
- [©️ Legal](#️-Legal)


## 📝 Description

This is a repackaging of the compiled iOS and Android modules for [Ti.Animation](https://github.com/m1ga/ti.animation) to allow for installation via npm.

## 🚀 Getting Started

### Install `@titanium/lottie` in root of project

```
npm install @titanium/lottie
```


### Create a View

```js
const lottie = require('@titanium/lottie');

const = lottie.createAnimationView({
  file: 'file.json',
  loop: false,
  autoStart: false
});
```


## ✨Features

iOS: `ti.animation 2.0.0`
Android: `ti.animation 3.0.0`

* [x] Display Lottie animations

## Library versions:

The Titanium modules use external libraries

|Library|Platform|Version|Build Date|
|---|---|---|---|
| [Airbnb Lottie](https://github.com/airbnb/lottie-android) | Android | 2.6.1 | 2018/09/06 |
| [Airbnb Lottie](https://github.com/airbnb/lottie-ios) | iOS | 2.5.2 | 2018/12/10 |





## 📚Learn More

- [Ti.Animation GitHub Repo](https://github.com/m1ga/ti.animation) - Repo for Ti.Animations modules
- [LottieFiles](http://www.lottiefiles.com/) - Free Lottie animations


## 📣 Feedback

Have an idea or a comment?  [Join in the conversation here](https://github.com/brentonhouse/titanium-lottie/issues)! 

## ©️ Legal

Modules are licensed under Apache 2.0 from https://github.com/appcelerator-modules/titanium-lottie

Alloy is developed by Appcelerator and the community and is Copyright © 2012-Present by Appcelerator, Inc. All Rights Reserved.

Alloy is made available under the Apache Public License, version 2. See their license file for more information.

Appcelerator is a registered trademark of Appcelerator, Inc. Titanium is a registered trademark of Appcelerator, Inc. Please see the LEGAL information about using trademarks, privacy policy, terms of usage and other legal information at http://www.appcelerator.com/legal.