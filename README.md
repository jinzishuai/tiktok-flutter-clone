# TikTok Clone

A Tiktok App- Works on Android & iOS! 

## Features
- Authentication with Email & Password
- Uploading Videos with Caption
- Compressing Videos
- Generating Thumbnails Out of Video
- Displaying Videos with Caption
- Liking on Posts
- Commenting on Posts
- Liking the Comments
- Searching Users
- Following Users
- Displaying Followers, Following, Likes & Posts of User
- TikTok Like UI

## YouTube
I have created a tutorial based on this, do check it out on my channel [Rivaan Ranawat](https://youtu.be/4E4V9F3cbp4) 

<p align="center">
  <img width="600" src="https://github.com/RivaanRanawat/tiktok-flutter-clone/blob/master/screenshot.png" alt="Youtube Tutorial Image">
</p>


## Installation
After cloning this repository, migrate to ```tiktok-flutter-clone``` folder. Then, follow the following steps:
- Create Firebase Project: [tiktok-flutter-6adf4](https://console.firebase.google.com/project/tiktok-flutter-6adf4/overview)
- Enable Authentication of Email/Password
![image](https://user-images.githubusercontent.com/1074685/224767421-5a47e671-1ab7-4a97-954f-01951419f76b.png)
- Manually Create User (note that user registration doesn't seem to work)
![image](https://user-images.githubusercontent.com/1074685/224881164-874cd538-5bff-47f1-9839-a0658f80e997.png)
- Make Firestore Rules
- Configure app with firebase with `flutterfire configure`
![image](https://user-images.githubusercontent.com/1074685/224767199-778795cf-a522-4fcc-867f-11877a4db43a.png)
- Create Android & iOS Emulator/Simulator
Then run the following commands to run your app:
```bash
  flutter pub get
  open -a simulator (to get iOS Simulator)
  flutter run
```

## Tech Used
**Server**: Firebase Auth, Firebase Storage, Firebase Firestore

**Client**: Flutter, GetX

**Architecture**: MVC
    
## Feedback

If you have any feedback, please reach out to me at namanrivaan@gmail.com

