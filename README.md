# Showdist F-Droid repo

An F-Droid repository for [Showdist](https://github.com/carlosantoniocruz/showdist-android),
an AR tape measure and bubble level for Android. No ads, no account, works offline.

<img src="showdist-repo.png" width="96">

## Add the repo

In the F-Droid app, go to **Settings → Repositories → +** and add:

```
https://carlosantoniocruz.github.io/fdroid/repo?fingerprint=0E388F97C5AA696BAC88483E8B9423590223E2AF06954483282951D970555554
```

Or scan this QR code with your phone:

<img src="showdist-fdroid-qr.png" width="200">

Then search for **Showdist** and install it.

## Apps

| App | Version | Package |
|---|---|---|
| Showdist | 1.2 (3) | `com.showconfigs.showdist` |

Showdist needs a phone that supports **Google Play Services for AR (ARCore)**.
ARCore is proprietary Google software, so F-Droid marks the app with the
*Non-free dependency* anti-feature.

## Links

- Source code: [showdist-android](https://github.com/carlosantoniocruz/showdist-android)
- Issues: [showdist-android/issues](https://github.com/carlosantoniocruz/showdist-android/issues)
- [Privacy policy](https://carlosantoniocruz.github.io/showdist-privacy/)

## What's in here

- `repo/`: the signed F-Droid index and APKs, served by GitHub Pages
- `metadata/`: app descriptions, screenshots and changelogs used to build the index
