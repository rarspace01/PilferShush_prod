# PilferShush_prod
Android near-ultra high frequency (NUHF) listener with microphone polling and NUHF/ACR SDK detector  

Test application for researching methods of discovering use of audio beacons.
- compile API 28 (Pie, 9.0), Android Studio 3.2.1 stable, AndroidX libs
- Added full passive and active jammers run as a foreground service.
- Conform to PilferShush Jammer app release version 3.0.1
- rewrite AudioSettings and deps for use with Bundle

   vers. 3.0.1
   - min API 18 (4.3)
   - target API 26 (8.x)
   - compiled API 26 (8.x)

   testing devices
   - LOW : s4 I9195 (deprecated) 4.3.1 (18)(CyanogenMod 10.2, F-Droid)
   - SLO : Mts 5045D (fail, tainted) 6.0.1 (23) (CyanogenMod 13.0, GApps)
   - DEV : s5 G900I (tainted) 7.1.2 (25)(LineageOS 14.1, GApps)
   - HIGH : s5 G900P (user) 7.1.2 (25)(LineageOS 14.1, F-Droid)
 
 TODO:
 - scanner as a foreground service
 - rebuild scanner to allow different methods of scanning

# 2018 Kaputnik Go


Screenshots

- Update UI
<img src="https://github.com/kaputnikGo/PilferShush_prod/blob/master/images/updateUI-jammers.jpg" height="612px" />

- App open
<img src="https://github.com/kaputnikGo/PilferShush_prod/blob/master/images/app-open.jpg" height="612px" />

- Detailed View
<img src="https://github.com/kaputnikGo/PilferShush_prod/blob/master/images/detailed-view.jpg" height="612px" />

- Capture live
<img src="https://github.com/kaputnikGo/PilferShush_prod/blob/master/images/capture-live.jpg" height="612px" />

- Post capture
<img src="https://github.com/kaputnikGo/PilferShush_prod/blob/master/images/post_capture.jpg" height="612px" />

- Option menu
<img src="https://github.com/kaputnikGo/PilferShush_prod/blob/master/images/option-menu.jpg" height="612px" />
