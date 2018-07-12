# Realtime polls App

This app mimics a typical twitter poll. A user votes for their option and see the results live. The app also sends notifications when someone has voted. There is a tutorial [here](https://pusher.com/tutorials/android-poll-push-notifications) to guide you.

## Getting Started

Clone the repository. The repository contains two folders, open the app in your Android studio. Replace the `google-services.json` file with the one from your 
Firebase dashboard. Replace the key holders in the app with the keys from your Pusher Beams and Pusher Channels dashboard then run your app.

Open the server folder and run this this command to get your server up: 

```
flask run
```

### Prerequisites

You need the following installed:

* [Android Studio](https://developer.android.com/studio/index)
* [Flask](http://flask.pocoo.org/)
* [Pusher Beams app](https://dash.pusher.com/beams)
* [Pusher Channels app](https://dashboard.pusher.com/)


## Built With

* [Kotlin](https://kotlinlang.org/) - Used to build the Android client
* [Pusher](https://pusher.com/) - APIs to enable devs building realtime features
* [Flask](http://flask.pocoo.org//) - Used to build the server

## Acknowledgments
