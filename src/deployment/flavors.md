---
title: Creating flavors for Flutter
short-title: Flavors
description: How to create build flavors specific to different release types or development environments.
---

{% comment %}
Eventually, we should actually include instructions,
but by platform and we can then move the platform-specific
instructions to /development/platform-integration/macos
or ios or android, etc.
sz: Yes, I've already asked Shamira (who will be working
on the new docs), to plan for multiple pages.
{% endcomment %}

Do you need to set up product flavors for different development
environments or release types?
The community has written some articles and packages you might find useful.
These articles address flavors for both iOS and Android.

* [Creating flavors of a Flutter app][]
* [Flavoring Flutter][]
* [Flutter Ready to Go][]
* [Build flavors in Flutter (Android and iOS)
  with different Firebase projects per flavor][]
* [Flutter 1.17 — no more Flavors, no more iOS Schemas.
  Command argument that changes everything][]
* [Multi-environment Flutter Projects with Flavors][]
  (including support for web, Firebase and FlutterFire CLI)

The following packages are listed alphabetically:

* [`flutter_flavor`][]
* [`flutter_flavorizr`][]

[Creating flavors of a Flutter app]: https://cogitas.net/creating-flavors-of-a-flutter-app/
[Flavoring Flutter]: {{site.medium}}/@salvatoregiordanoo/flavoring-flutter-392aaa875f36
[Flutter Ready to Go]: {{site.medium}}/flutter-community/flutter-ready-to-go-e59873f9d7de
[Build flavors in Flutter (Android and iOS) with different Firebase projects per flavor]: {{site.medium}}/@animeshjain/build-flavors-in-flutter-android-and-ios-with-different-firebase-projects-per-flavor-27c5c5dac10b
[Flutter 1.17 — no more Flavors, no more iOS Schemas. Command argument that changes everything]: {{site.medium}}/@tatsu.ukraine/flutter-1-17-no-more-flavors-no-more-ios-schemas-command-argument-that-solves-everything-8b145ed4285d
[Multi-environment Flutter Projects with Flavors]: https://sebastien-arbogast.com/2022/05/02/multi-environment-flutter-projects-with-flavors/
[`flutter_flavor`]: {{site.pub}}/packages/flutter_flavor
[`flutter_flavorizr`]: {{site.pub}}/packages/flutter_flavorizr
