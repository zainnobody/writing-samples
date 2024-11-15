---
title: Creating the Mobile App
sidebar: doc_sidebar
permalink: create-app.html
toc: false

---
Use the app SDK to create your app. While you are welcome to develop from scratch if that suits you, we highly recommend starting with and customizing the starter app and following this development workflow:

1. If you are not already familiar with developing code in Android Studio, take a look at [https://developer.android.com/studio/intro](https://developer.android.com/studio/intro){:target="_blank"}.
2. In Android Studio, clone the [starter-app](https://github.com/S-HealthStack/starter-app){:target="_blank"} GitHub repository to retrieve the app starter code.
3. Edit the code in the `main` branch to customize it for your study.

   > The `mg-study`branch contains the completed code described in the tutorial and demoed at the Samsung Developer Conference (SDC22). Compare  the `main` and `mg-study` branches to see the minimal changes needed to make the app your own.

The app needs to be able to:

* Determine participant eligibility.
* Acquire informed consent from participants.
* Register participants.
* Specify the data to collect (for example, heart rate, step count, and blood pressure).
* Present surveys.
* Collect and pass data on for storage.
* Present data visualizations to keep participants engaged.

# Full-Stack Implementations

With the full stack, an Android mobile app receives data from the wearable device and transmits the data to the backend system. 

# SDK-Only Implementations

With just the SDK, an Android mobile app receives data from the wearable device and stores the data in your own backend or on the device itself. 

