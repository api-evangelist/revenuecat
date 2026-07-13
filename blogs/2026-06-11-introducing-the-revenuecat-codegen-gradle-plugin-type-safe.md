---
title: "Introducing the RevenueCat Codegen Gradle Plugin: type safe entitlements and offerings on Android"
url: "https://www.revenuecat.com/blog/engineering/android-codegen/"
date: "2026-06-11"
author: ""
feed_url: "https://www.revenuecat.com/blog/rss.xml"
---
<p class="wp-block-paragraph">Every RevenueCat integration shares the same quiet liability: the string keys. Your entitlements, offerings, and packages live in the RevenueCat dashboard, and your Kotlin code reaches for them with raw strings like&nbsp;<code>entitlements["premium_access"]</code>. The compiler cannot verify those strings, the IDE cannot autocomplete them, and a single typo ships as a
