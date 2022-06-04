# React-Native-Google-Login
**Delete debug.keystore from App dir.** 
in App Dir only " **keytool -genkey -v -keystore debug.keystore -alias androiddebugkey -storepass android -keypass android -keyalg RSA -validity 10000**" to generate new debug.keystore.
To get SHA1 key , keytool -keystore debug.keystore -list -v in App dir only
