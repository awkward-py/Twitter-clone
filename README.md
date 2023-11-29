## Twitter Clone in Flutter - Fwitter

Welcome to **Fwitter**, a Twitter clone built using Flutter and powered by Firebase for authentication, real-time updates, Firestore database, and storage. Fwitter aims to replicate the essential features of Twitter in a Flutter app.

![GitHub stars](https://img.shields.io/github/stars/awkward-py/Twitter-clone?style=social)
![GitHub forks](https://img.shields.io/github/forks/awkward-py/Twitter-clone?style=social)


### Features

* Fwitter now uses both Firebase `Realtime` and `Firestore` databases. Choose your preferred branch for database usage.
  * The `firestore` branch uses Firestore.
  * The `master` and `realtime_db` branches use Firebase Realtime database.

For a comprehensive list of app features, you can refer to the project section [here](https://github.com/awkward-py/Twitter-clone/projects/1).


### Directory Structure

```
|-- lib
|   |-- helper
|   |   |-- constant.dart
|   |   |-- customRoute.dart
|   |   |-- enum.dart
|   |   |-- routes.dart
|   |   |-- theme.dart
|   |   |-- utility.dart
|   |   '-- validator.dart
|   |-- main.dart
|   |-- model
|   |   |-- chatModel.dart
|   |   |-- feedModel.dart
|   |   |-- notificationModel.dart
|   |   '-- user.dart
|   |-- page
|   |   |-- Auth
|   |   |   |-- forgetPasswordPage.dart
|   |   |   |-- selectAuthMethod.dart
|   |   |   |-- signin.dart
|   |   |   |-- signup.dart
|   |   |   |-- verifyEmail.dart
|   |   |   '-- widget
|   |   |       '-- googleLoginButton.dart
|   |   |-- common
|   |   |   |-- sidebar.dart
|   |   |   |-- splash.dart
|   |   |   |-- usersListPage.dart
|   |   |   '-- widget
|   |   |       '-- userListWidget.dart
|   |   |-- feed
|   |   |   |-- composeTweet
|   |   |   |   |-- composeTweet.dart
|   |   |   |   |-- state
|   |   |   |   |   '-- composeTweetState.dart
|   |   |   |   '-- widget
|   |   |   |       |-- composeBottomIconWidget.dart
|   |   |   |       |-- composeTweetImage.dart
|   |   |   |       '-- widgetView.dart
|   |   |   |-- feedPage.dart
|   |   |   |-- feedPostDetail.dart
|   |   |   '-- imageViewPage.dart
|   |   |-- homePage.dart
|   |   |-- message
|   |   |   |-- chatListPage.dart
|   |   |   |-- chatScreenPage.dart
|   |   |   |-- conversationInformation
|   |   |   |   '-- conversationInformation.dart
|   |   |   '-- newMessagePage.dart
|   |   |-- notification
|   |   |   '-- notificationPage.dart
|   |   |-- profile
|   |   |   |-- EditProfilePage.dart
|   |   |   |-- follow
|   |   |   |   |-- followerListPage.dart
|   |   |   |   '-- followingListPage.dart
|   |   |   |-- profileImageView.dart
|   |   |   |-- profilePage.dart
|   |   |   '-- widgets
|   |   |       '-- tabPainter.dart
|   |   |-- search
|   |   |   '-- SearchPage.dart
|   |   '-- settings
|   |       |-- accountSettings
|   |       |   |-- about
|   |       |   |   '-- aboutTwitter.dart
|   |       |   |-- accessibility
|   |       |   |   '-- accessibility.dart
|   |       |   |-- accountSettingsPage.dart
|   |       |   |-- contentPrefrences
|   |       |   |   |-- contentPreference.dart
|   |       |   |   '-- trends
|   |       |   |       '-- trendsPage.dart
|   |       |   |-- dataUsage
|   |       |   |   '-- dataUsagePage.dart
|   |       |   |-- displaySettings
|   |       |   |   '-- displayAndSoundPage.dart
|   |       |   |-- notifications
|   |       |   |   '-- notificationPage.dart
|   |       |   |-- privacyAndSafety
|   |       |   |   |-- directMessage
|   |       |   |   |   '-- directMessage.dart
|   |       |   |   '-- privacyAndSafetyPage.dart
|   |       |   '-- proxy
|   |       |       '-- proxyPage.dart
|   |       |-- settingsAndPrivacyPage.dart
|   |       '-- widgets
|   |           |-- headerWidget.dart
|   |           |-- settingsAppbar.dart
|   |           '-- settingsRowWidget.dart
|   |-- state
|   |   |-- appState.dart
|   |   |-- authState.dart
|   |   |-- chats
|   |   |   '-- chatState.dart
|   |   |-- feedState.dart
|   |   |-- notificationState.dart
|   |   '-- searchState.dart
|   '-- widgets
|       |-- bottomMenuBar
|       |   |-- HalfPainter.dart
|       |   |-- bottomMenuBar.dart
|       |   '-- tabItem.dart
|       |-- customAppBar.dart
|       |-- customWidgets.dart
|       |-- newWidget
|       |   |-- customClipper.dart
|       |   |-- customLoader.dart
|       |   |-- customProgressbar.dart
|       |   |-- customUrlText.dart
|       |   |-- emptyList.dart
|       |   |-- rippleButton.dart
|       |   '-- title_text.dart
|       '-- tweet
|           |-- tweet.dart
|           '-- widgets
|               |-- parentTweet.dart
|               |-- retweetWidget.dart
|               |-- tweetBottomSheet.dart
|               |-- tweetIconsRow.dart
|               |-- tweetImage.dart
|               '-- unavailableTweet.dart
|-- pubspec.yaml
```


### Getting Started

To get started with this project, please refer to the project setup instructions in the [Wiki](https://github.com/awkward-py/Twitter-clone/wiki/Gettings-Started) section.

### Dependencies

Fwitter relies on several dependencies to function properly. Some of the key dependencies include:

* [intl](https://pub.dev/packages/intl)
* [uuid](https://pub.dev/packages/uuid)
* [http](https://pub.dev/packages/http)
* [share](https://pub.dev/packages/share)
* [provider](https://pub.dev/packages/provider)
* [url_launcher](https://pub.dev/packages/url_launcher)
* [google_fonts](https://pub.dev/packages/google_fonts)
* [image_picker](https://pub.dev/packages/image_picker)
* [firebase_auth](https://pub.dev/packages/firebase_auth)
* [google_sign_in](https://pub.dev/packages/google_sign_in)
* [firebase_analytics](https://pub.dev/packages/firebase_analytics)
* [firebase_database](https://pub.dev/packages/firebase_database)
* [shared_preferences](https://pub.dev/packages/shared_preferences)
* [flutter_advanced_networkimage](https://pub.dev/packages/flutter_advanced_networkimage)

### Contributing

We welcome contributions to Fwitter. If you want to add a new feature or make changes to an existing one, please review our [contribution guide](https://github.com/awkward-py/Twitter-clone/blob/master/CONTRIBUTING.md) and submit a [pull request](https://github.com/awkward-py/Twitter-clone/pulls). We appreciate all contributions, and we aim to respond to issues and requests within 24-48 hours.

### Created & Maintained By

- [Awkward-py](https://github.com/awkward-py)
  - [Twitter](https://www.twitter.com/awkwardpy)

