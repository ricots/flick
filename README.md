# Flick
An Android chat client powered by Firebase

**Status:** Under development

![alt tag](http://www.vathsav.com/img/real_time_chat_client_using_firebase/chat_emulators.gif)

**Todo:**
* Chat functionality
* Chat invites
* Offline data persistence
* XMPP server scripts for upstream push notifications.
* Google authentication
* Chat groups

## Setup

**Create 2 variables in your gradle.properties.**

```
FirebaseRootUrl = "https://<your-project-id>.firebaseio.com"
FlickOAuthClientId = "<key>.apps.googleusercontent.com"
```

Refer [Authenticate with Firebase](https://firebase.google.com/docs/auth/android/google-signin#authenticate_with_firebase)

## License

Copyright 2016 Vathsav Harikrishnan

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html
