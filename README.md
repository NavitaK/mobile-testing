# Mobile testing

This is a curated list of mobile testing related resources.

# Table of contents

* [Books](#books)
* [Mind maps, mnemonics](#mind-maps-mnemonics)
* Android
  * [Official documentation](#official-documentation-android)
  * [Official presentations](#official-presentations-android)
  * [Tools](#tools-android)
  * [Virtualization](#virtualization-android)
  * [Local device farm](#local-device-farm-android)
  * [Native Android test automation tools and libraries](#native-android-test-automation-tools-and-libraries)
  * [Native Android test automation presentations](#native-android-test-automation-presentations)
* [Mobile cloud services](#mobile-cloud-services)
* [Test automation tools evaluation](#test-automation-tools-evaluation)

# Books

* [Hands-On Mobile App Testing: A Guide for Mobile Testers and Anyone Involved in the Mobile App Business by Daniel Knott](https://www.amazon.com/Hands-Mobile-App-Testing-Involved/dp/0134191714) (2015)
* [Mobile Testing Tips: Experiences & Realities by Baris Sarialioglu](https://www.amazon.com/Mobile-Testing-Tips-Experiences-Realities/dp/6056414035) (2015)
* [Tap Into Mobile Application Testing by Jonathan Kohl](https://leanpub.com/testmobileapps) (2017)

# Mind maps, mnemonics

* [Mind Maps: for Fast and Effective Testing](https://badootech.badoo.com/mind-maps-for-fast-and-effective-testing-30aab6bea6f4)

# Official documentation (Android)

* [Test apps on Android](https://developer.android.com/training/testing/)
* [Android Testing Codelab](https://codelabs.developers.google.com/codelabs/android-testing/index.html#0)
* [AndroidX Test release notes](https://developer.android.com/training/testing/release-notes)

# Official presentations (Android)

* [Testing Android Apps at Scale with Nitrogen (Android Dev Summit '18)](https://www.youtube.com/watch?v=-_kZC29sWAo)
* [Testing Rebooted (with AndroidX Test) (Android Dev Summit '18)](https://www.youtube.com/watch?v=4m2yYSTdvIg)
* [Frictionless Android testing: write once, run everywhere (Google I/O '18)](https://www.youtube.com/watch?v=wYMIadv9iF8)
* [Test-Driven Development on Android with the Android Testing Support Library (Google I/O '17)](https://www.youtube.com/watch?v=pK7W5npkhho)

# Tools (Android)

* [adb](https://developer.android.com/studio/command-line/adb) - a versatile command-line tool that lets you communicate with a device
* [logcat](https://developer.android.com/studio/command-line/logcat) - a command-line tool that dumps a log of system messages, including stack traces when the device throws an error and messages that you have written from your app with the Log class
* [Developer options](https://developer.android.com/studio/debug/dev-options) - lets you configure system behaviors that help you profile and debug your app performance
* [Android Profiler](https://developer.android.com/studio/profile/android-profiler) - provides real-time data to help you to understand how your app uses CPU, memory, network, and battery resources
* [Charles](https://www.charlesproxy.com/)/[Fiddler](https://www.telerik.com/fiddler) – debug proxy
* [Crashlytics](https://docs.fabric.io/apple/crashlytics/overview.html) – crash reporting solution
* [HockeyApp](https://hockeyapp.net/apps/) - a service that allows developers to recruit and manage testers, distribute apps, and collect crash reports, among other things

# Virtualization (Android)

* [Selenoid](https://github.com/aerokube/selenoid) - Selenium Hub successor running browsers and Android emulators within containers
* [Docker-Android](https://github.com/butomo1989/docker-android) - Android in docker solution with noVNC supported and video recording
* [swarmer](https://github.com/gojuno/swarmer) - Reactive tool to create and start multiple Android Emulators in parallel
* [fastlane-plugin-automated-test-emulator-run](https://github.com/AzimoLabs/fastlane-plugin-automated-test-emulator-run) - Plugin dedicated for Android platform. Wraps gradle task/shell command used for launching instrumented tests. Provides start of as many AVDs with various configs as needed before test run, waits for boot, kills emulators and deletes them from hdd after tests are finished or disturbed.

# Local device farm (Android)

* [OpenSTF](https://openstf.io/) - Control and manage Android devices from your browser

# Native Android test automation tools and libraries

* [Espresso](https://developer.android.com/training/testing/espresso/)
* [Android Test Orchestrator](https://developer.android.com/training/testing/junit-runner#using-android-test-orchestrator) - run each test in it’s own instrumentation process, clear app state between tests
* [Kakao](https://github.com/agoda-com/Kakao) – “Nice and simple DSL for Espresso in Kotlin”
* [Barista](https://github.com/SchibstedSpain/Barista) – “The guy who serves a great Espresso”

# Native Android test automation presentations

* [A practical guide to writing solid UI tests on Android by Valera Zakharov](https://slideslive.com/38897360/a-practical-guide-to-writing-solid-ui-tests-on-android-en)
* [UI testing is so easy - said no developer ever by Valera Zakharov](https://www.youtube.com/watch?v=SkkO6x6LhCQ)

# Mobile cloud services

* [Firebase Test lab](https://firebase.google.com/docs/test-lab/) (Android and iOS) - Test your app on devices hosted in a Google data center

# Test automation tools evaluation

* [The Shifting Landscape of Mobile Automation](https://www.youtube.com/watch?v=AV8p2aeqsOg)
* [Mobile automation: three act tragedy](https://seleniumcamp.com/talk/mobile-automation-three-act-tragedy/) (Ru)
* [Appium vs Espresso. Что выбрать и как использовать?](https://www.youtube.com/watch?v=A1_Xzcs_Fec) (Ru)
* [СI/CD в iOS и Android](https://www.youtube.com/watch?v=y0wxtyUQZ1I) (Ru)
* [Do Androids Dream of UI Testing?](https://arturdryomov.online/posts/do-androids-dream-of-ui-testing/)
