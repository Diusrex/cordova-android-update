Cordova plugin for Android
===================================================
Is meant to bring bring up play store to update current app

Installation
---------------------------------------------------
Inside the cordova project:

```
cordova plugin add https://github.com/Diusrex/cordova-android-update
```


Usage
-----------------------------------------------------
To use inside of your javascript code, use the following line:

```javascript
updateApp(shouldQuitApp, successFunction, errorFunction);
```

<b>shouldQuitApp</b>: Will determine if the app should be finished upon the play store being opened. NOTE: Does NOT guarantee that the user will update the app, just that they will be brought to the play store for the app.

<b>success/errorFunction</b>: The functions that will be called on error and success.
