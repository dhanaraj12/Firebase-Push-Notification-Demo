
## Introduction
Firebase Cloud Messaging (FCM) is a cross-platform messaging solution that lets you reliably deliver messages at no cost. You can find more info here : https://firebase.google.com/docs/cloud-messaging/


This repo is showing you Simple Firebase Implementation with implemented receiving custom data (currently int ID) that you can use to trigger specific action in application

##IMPORTANT

App won't work if you don't create your own google-services.json on https://console.firebase.google.com

## Setup
- Add internet permission in your app
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />

- Create new account on https://console.firebase.google.com/ or use existing one
- Create new project for Android
- Press add Firebase to your Android app button and follow instructions
- Copy MyFirebaseInstanceIDService and MyFirebaseMessagingService classes
- Add them to manifest  
- Send push notification from Firebase Console

## License

Copyright 2016 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor license agreements. See the NOTICE file distributed with this work for additional information regarding copyright ownership. The ASF licenses this file to you under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
