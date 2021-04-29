# Flutter Development Environment Setup

To see all connected devices/emulators:
`flutter devices`

To run flutter on a specific device( for example: chrome):
`flutter run -d chrome`

Run flutter on all connected devices/emulators:
`flutter run -d all`

Press `r` to hot reload for all


##### Generate keytool in windows:
Go to command line C:\Program Files\Android\Android Studio\jre\bin\
`keytool -genkey -v -keystore "C:\Program Files\Android\Android Studio\jre\bin\key.pfx" -storetype PKCS12 -keyalg RSA -keysize 2048 -validity 10000 -alias key`

Put the key in android/app/ then add to gitignore

#### For Android:
To build app bundle
`flutter build appbundle`

#### For Web:
`flutter build web`