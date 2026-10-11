# Apex TV signed menu updates

Public update feed for Apex TV, a personal, unofficial F1 TV client for Samsung Tizen televisions. The signed menu is version 0.5.4.

The TV verifies the pinned RSA signature, the SHA-256 hash of each file, compatible shell/version metadata and the persisted update floor before installing an update. Updates are applied while the Home menu is idle or when explicitly requested in Settings. Watching and menu updates do not require the companion PC once this menu is installed.

This repository contains only public menu assets and their signed manifest. It does not contain account sessions, passwords, Samsung certificates, TV pairing/configuration files, private signing keys or device identifiers. A valid F1 TV subscription is required; normal F1 entitlement and DRM remain in use. The feed is not an official Formula 1, Apple or Samsung product.

Layout reference: [Apple TV app navigation](https://support.apple.com/en-euro/guide/tvapp/atvb5e608b5e/1.0/web/1.0). Bundled third-party components retain their notices in the JavaScript file. The complete project and a distributable Samsung store app are not published here.

Version 0.5.4 moves F1 Live and International to language/audio choices, keeps driver POV and data views in camera choices, and lets Back hide player controls before leaving playback. Source and a public installer package: https://github.com/Pajuodelis/apex-tv
