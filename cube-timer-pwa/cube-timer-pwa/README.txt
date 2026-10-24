CUBE TIMER — PWA STARTER

This folder contains the original timer with only the basic PWA wiring added:
- index.html: your existing app, with manifest and service-worker links
- manifest.json: installable-app name and icons
- sw.js: caches the app files so they can be opened offline after first loading
- icons/: temporary cube logo in 192px and 512px sizes

IMPORTANT
1. Keep this whole folder together; do not move the files out of it.
2. Your original upload has not been overwritten. This starter uses a copy called index.html.
3. A service worker does not run from a file:/// address. The app must be served by localhost or HTTPS to test offline/install behavior. We will set up the easiest way to do that as the next step.
4. This is the first conversion step, not yet an Android APK. Timer behavior and data storage have not been redesigned.
