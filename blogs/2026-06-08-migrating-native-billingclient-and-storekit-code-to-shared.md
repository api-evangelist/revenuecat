---
title: "Migrating native BillingClient and StoreKit code to shared Kotlin Multiplatform in-app purchases"
url: "https://www.revenuecat.com/blog/engineering/kmp-migration/"
date: "2026-06-08"
author: ""
feed_url: "https://www.revenuecat.com/blog/rss.xml"
---
<p class="wp-block-paragraph">Most teams that adopt Kotlin Multiplatform share their networking, models, and business logic first, and leave in-app purchases for last. Billing is the one layer where Android and iOS share almost nothing: a&nbsp;<code>BillingClient</code>&nbsp;connection and a&nbsp;<code>PurchasesUpdatedListener</code>&nbsp;on one side, a StoreKit transaction listener and manual rec
