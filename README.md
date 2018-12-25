# Mobile testing

This is a curated list of mobile testing related resources.

# Table of contents

* [Books](#blue_book-books)
* [Mind maps, mnemonics](#world_map-mind-maps-mnemonics)
* **Android**
  * [Official documentation](#scroll-official-documentation-android)
  * [Official presentations](#clapper-official-presentations-android)
  * [Tools](#hammer_and_wrench-tools-android)
  * [Virtualization](#ghost-virtualization-android)
  * [Local device farm](#iphone-local-device-farm-android)
  * [Native Android test automation tools and libraries](#hammer_and_wrench-native-android-test-automation-tools-and-libraries)
  * [Native Android test automation presentations](#clapper-native-android-test-automation-presentations)
* **iOS**
  * [Official documentation](#scroll-official-documentation-ios)
  * [Official presentations](#clapper-official-presentations-ios)
  * [Native iOS test automation presentations](#clapper-native-ios-test-automation-presentations)
* [Mobile cloud services](#cloud-mobile-cloud-services)
* [Mobile cloud presentations](#cloud-mobile-cloud-presentations)
* [Test automation tools evaluation](#hammer_and_wrench-test-automation-tools-evaluation)
* [Cross-platform best practices](#thumbsup-cross-platform-best-practices)

# :blue_book: Books

* [Tap Into Mobile Application Testing](https://leanpub.com/testmobileapps) by Jonathan Kohl (2017)
* [Hands-On Mobile App Testing: A Guide for Mobile Testers and Anyone Involved in the Mobile App Business](https://www.amazon.com/Hands-Mobile-App-Testing-Involved/dp/0134191714) by Daniel Knott (2015)
* [Mobile Testing Tips: Experiences & Realities](https://www.amazon.com/Mobile-Testing-Tips-Experiences-Realities/dp/6056414035) by Baris Sarialioglu (2015)

# :world_map: Mind maps, mnemonics

* [Mind Maps: for Fast and Effective Testing](https://badootech.badoo.com/mind-maps-for-fast-and-effective-testing-30aab6bea6f4)

# :scroll: Official documentation (Android)

* [Test apps on Android](https://developer.android.com/training/testing/)
* [Android Testing Codelab](https://codelabs.developers.google.com/codelabs/android-testing/index.html#0)
* [Using Firebase Test Lab to Improve the Quality of your Mobile Apps](https://codelabs.developers.google.com/codelabs/firebase-test-lab/index.html)
* [Automated Performance Testing Codelab](https://codelabs.developers.google.com/codelabs/android-perf-testing/index.html#0)
* [AndroidX Test release notes](https://developer.android.com/training/testing/release-notes)
* [Test your app's accessibility](https://developer.android.com/training/accessibility/testing)

# :clapper: Official presentations (Android)

* [Testing Android Apps at Scale with Nitrogen](https://www.youtube.com/watch?v=-_kZC29sWAo) (Android Dev Summit '18)
* [Testing Rebooted (with AndroidX Test)](https://www.youtube.com/watch?v=4m2yYSTdvIg) (Android Dev Summit '18)
* [Frictionless Android testing: write once, run everywhere](https://www.youtube.com/watch?v=wYMIadv9iF8) (Google I/O '18)
* [Test-Driven Development on Android with the Android Testing Support Library](https://www.youtube.com/watch?v=pK7W5npkhho) (Google I/O '17)
* [Going Green: Cleaning up the Toxic Mobile Environment](https://www.youtube.com/watch?v=aHcmsK9jfGU) (GTAC 2014)

# :hammer_and_wrench: Tools (Android)

* [adb](https://developer.android.com/studio/command-line/adb) - a versatile command-line tool that lets you communicate with a device
* [logcat](https://developer.android.com/studio/command-line/logcat) - a command-line tool that dumps a log of system messages, including stack traces when the device throws an error and messages that you have written from your app with the Log class
* [pidcat](https://github.com/JakeWharton/pidcat) - Colored logcat script which only shows log entries for a specific application package
* [Developer options](https://developer.android.com/studio/debug/dev-options) - lets you configure system behaviors that help you profile and debug your app performance
* [Android Profiler](https://developer.android.com/studio/profile/android-profiler) - provides real-time data to help you to understand how your app uses CPU, memory, network, and battery resources
* [Charles](https://www.charlesproxy.com/)/[Fiddler](https://www.telerik.com/fiddler) – debug proxy
* [Crashlytics](https://docs.fabric.io/apple/crashlytics/overview.html) – crash reporting solution
* [HockeyApp](https://hockeyapp.net/apps/) - a service that allows developers to recruit and manage testers, distribute apps, and collect crash reports, among other things

# :ghost: Virtualization (Android)

* [Selenoid](https://github.com/aerokube/selenoid) - Selenium Hub successor running browsers and Android emulators within containers
* [Docker-Android](https://github.com/butomo1989/docker-android) - Android in docker solution with noVNC supported and video recording
* [swarmer](https://github.com/gojuno/swarmer) - Reactive tool to create and start multiple Android Emulators in parallel
* [fastlane-plugin-automated-test-emulator-run](https://github.com/AzimoLabs/fastlane-plugin-automated-test-emulator-run) - Plugin dedicated for Android platform. Wraps gradle task/shell command used for launching instrumented tests. Provides start of as many AVDs with various configs as needed before test run, waits for boot, kills emulators and deletes them from hdd after tests are finished or disturbed.

# :iphone: Local device farm (Android)

* [OpenSTF](https://openstf.io/) - Control and manage Android devices from your browser

# :hammer_and_wrench: Native Android test automation tools and libraries

* [Espresso](https://developer.android.com/training/testing/espresso/) - The Espresso testing framework, provided by AndroidX Test, provides APIs for writing UI tests to simulate user interactions within a single target app
* [Wait for it… IdlingResource and ConditionWatcher](https://medium.com/azimolabs/wait-for-it-idlingresource-and-conditionwatcher-602055f32356)
* [Android Test Orchestrator](https://developer.android.com/training/testing/junit-runner#using-android-test-orchestrator) - run each test in it’s own instrumentation process, clear app state between tests
* [Source code for Android Test](https://github.com/android/android-test)
* [StackOverflow for Espresso](https://stackoverflow.com/questions/tagged/android-espresso)
* [Issue Tracker for Android Test](https://issuetracker.google.com/issues?q=componentid:192735%2B)
* [Kakao](https://github.com/agoda-com/Kakao) – “Nice and simple DSL for Espresso in Kotlin”
* [Barista](https://github.com/SchibstedSpain/Barista) – “The guy who serves a great Espresso”
* [Robolectric](http://robolectric.org/) - a framework that brings fast and reliable unit tests to Android. Tests run inside the JVM on your workstation in seconds

# :clapper: Native Android test automation presentations

* [A practical guide to writing solid UI tests on Android](https://slideslive.com/38897360/a-practical-guide-to-writing-solid-ui-tests-on-android-en) by Valera Zakharov
* [UI testing is so easy - said no developer ever](https://www.youtube.com/watch?v=SkkO6x6LhCQ) by Valera Zakharov

# :scroll: Official documentation (iOS)

* [XCTest](https://developer.apple.com/documentation/xctest)
* [About Testing with Xcode](https://developer.android.com/training/testing/) (archived)

# :clapper: Official presentations (iOS)

* [Testing Tips & Tricks](https://developer.apple.com/videos/play/wwdc2018/417) (WWDC 2018)
* [What's New in Testing](https://developer.apple.com/videos/play/wwdc2018/403/) (WWDC 2018)
* [Engineering for Testability](https://developer.apple.com/videos/play/wwdc2017/414/) (WWDC 2017)
* [What's New in Testing](https://developer.apple.com/videos/play/wwdc2017/409) (WWDC 2017)
* [Advanced Testing and Continuous Integration](https://developer.apple.com/videos/play/wwdc2016/409) (WWDC 2016)
* [Continuous Integration and Code Coverage in Xcode](https://developer.apple.com/videos/play/wwdc2015/410/) (WWDC 2015)
* [UI Testing in Xcode](https://developer.apple.com/videos/wwdc/2015/?id=406) (WWDC 2015)

# :clapper: Native iOS test automation presentations

* [iOS Test Automation at Continuous Delivery Pipeline](https://www.youtube.com/watch?v=ImR956OKTn4) by Igor Dorovskikh
* [Scalable iOS Test Automation with XCUITest and Swift 3](https://www.youtube.com/watch?v=xOxvCcidIf0) by Igor Dorovskikh

# :cloud: Mobile cloud services

* [Firebase Test lab](https://firebase.google.com/docs/test-lab/) (Android and iOS) - Test your app on devices hosted in a Google data center

# :cloud: Mobile cloud presentations

* [Тестирование мобильных приложений используя облачные сервисы](https://www.youtube.com/watch?v=fLb2T02UBMI) (Ru) by Дмитрий Лемешко (2017-02-26)

# :hammer_and_wrench: Test automation tools evaluation

* [The Shifting Landscape of Mobile Automation](https://www.youtube.com/watch?v=AV8p2aeqsOg)
* [Mobile automation: three act tragedy](https://seleniumcamp.com/talk/mobile-automation-three-act-tragedy/) (Ru)
* [Appium vs Espresso. Что выбрать и как использовать?](https://www.youtube.com/watch?v=A1_Xzcs_Fec) (Ru)
* [СI/CD в iOS и Android](https://www.youtube.com/watch?v=y0wxtyUQZ1I) (Ru)
* [Do Androids Dream of UI Testing?](https://arturdryomov.online/posts/do-androids-dream-of-ui-testing/)

# :thumbsup: Cross-platform best practices

* [Making Your Appium Tests Fast and Reliable, Part 5: Setting Up App State](https://appiumpro.com/editions/23)