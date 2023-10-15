YouTube: 18.40.34  
Music-Extended (arm64-v8a): 6.22.51  
Music-Extended (arm-v7a): 6.22.51  
YouTube-Extended: 18.40.34  
Music (arm64-v8a): 6.22.51  
Music (arm-v7a): 6.22.51  
Twitter: 10.11.0-release.0  
Twitch: 16.6.2  
Reddit: 2023.40.0  
Tasker: 6.2.12-rc  
TickTick: 6.7.0.7  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.0.3-all.jar  
Integrations: inotia00/revanced-integrations-0.119.12.apk  
Patches: inotia00/revanced-patches-2.193.12.jar  

YouTube
==
- feat(YouTube): add `Enable gradient loading screen` patch. if you disable `Enable gradient loading screen`, gradient loading screen will be disabled. [screenshot](https://www.reddit.com/r/youtube/comments/15q5xb5/weird_gradient_colored_skeleton_loading_screen/)
- feat(YouTube): change patch name `Language switch` → `Enable language switch`
- feat(YouTube/Enable language switch): now the `Enable language switch` switch has been added to the Miscellaneous settings, and if you disable `Enable language switch`, the language switch toggle will be hidden
- feat(YouTube/Hide shorts components): add support for new type of subscriptions button
- feat(YouTube/Hide shorts components): `Hide info panels` now also hides the panel for music information
- feat(YouTube/Settings): import/export settings are no longer Experimental Flags
- fix(YouTube/Bypass ambient mode restrictions): apply fingerprint compatible with wider version
- fix(YouTube/Enable new comment popup panels): change default value
- fix(YouTube/Hide channel watermark): watermark is not hidden https://github.com/inotia00/ReVanced_Extended/issues/1521
- fix(YouTube/Hide shorts components): like and dislike buttons cant be hidden https://github.com/inotia00/ReVanced_Extended/issues/1525
- fix(YouTube/Old quality layout · Old speed layout): old quality layout / custom playback speed not working in certain situations https://github.com/inotia00/ReVanced_Extended/issues/1507
- feat(YouTube/Translations): update translation
`Chinese Simplified`, `French`, `Greek`, `Italian`, `Korean`, `Russian`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- fix(YouTube Music/Hook download button): change the description of a setting https://github.com/inotia00/ReVanced_Extended/issues/1528
- feat(YouTube Music/Translations): update translation
`Greek`, `Korean`, `Polish`, `Russian`, `Spanish`, `Ukrainian`, `Vietnamese`


Etc
==
- When updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.12.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.12.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)


---
CLI: j-hc/revanced-cli-4.0.2-all.jar  
Integrations: ReVanced/revanced-integrations-0.119.2.apk  
Patches: ReVanced/revanced-patches-2.194.0.jar  

### [2.194.0](https://github.com/ReVanced/revanced-patches/compare/v2.193.0...v2.194.0) (2023-10-12)


### Bug Fixes

* **YouTube - ReturnYouTubeDislike:** Fix dislikes not showing on Shorts ([#3133](https://github.com/ReVanced/revanced-patches/issues/3133)) ([0e8a286](https://github.com/ReVanced/revanced-patches/commit/0e8a2868e8e4328a6f02fa31537abc5e5ed220eb))
* **YouTube - Spoof app version:** Recommend clearing the app data after turning off spoofing ([#3134](https://github.com/ReVanced/revanced-patches/issues/3134)) ([166bf5b](https://github.com/ReVanced/revanced-patches/commit/166bf5b1aec5f8868b3895f7e24d2abc9037a7de))


### Features

* **CieID:** Add `bypass root check` patch ([#3011](https://github.com/ReVanced/revanced-patches/issues/3011)) ([20cfa8a](https://github.com/ReVanced/revanced-patches/commit/20cfa8a5cdebc7e81128c820a2aa01415a068320))
* Do not support reading options from a properties file ([3d1c0c1](https://github.com/ReVanced/revanced-patches/commit/3d1c0c1a958271c358755220b97b9dd92eb81d54))
* Improve option descriptions and titles ([9f86daa](https://github.com/ReVanced/revanced-patches/commit/9f86daa82271591bcaa9144d300a4810458fdd28))




---  
