# doc-appium-playground

1.Install and Verify Node JS
  - download and install node.js
  - verify installation : node-v
2. verify npm : npm -v
3. Install and Verify Appium
  - npm install -g appium
  - appium
  - ctrl c (to close appium server)
4. Install Android Sdk and Platform Tools
  - download and setup android command line toos, extract and move to programs folder, set path and ANDROID_HOME
  - sdkmanager "platform-tools" "platforms;android-33" "system-images;android-33;google_apis;x86_64"
  - yes | sdkmanager --licenses
- avdmanager create avd -n Pixel_API33 -k "system-images;android-33;google_apis;x86_64"
- emulator avd Pixel_API33
- appium driver install uiautomator2
- appium driver doctor uiautomator2

--------------------------------------------------------------
- Requirement : node.js, npm, java, android tools, sdk, emulator
- Start / Stop appium server : appium / Ctrl C
