<h1 align="center">Welcome to YouTubeDownloader-AHK 👋</h1>
<p align="center">
  <img src="https://img.shields.io/badge/version-v0.5.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/AkshayCraZzY/YouTubeDownloader-AHK/blob/master/README.md">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/AkshayCraZzY/YouTubeDownloader-AHK/blob/master/LICENSE.md">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
  </a>
  <a href="https://twitter.com/Akshayparakh98">
    <img alt="Twitter: Akshayparakh98" src="https://img.shields.io/twitter/follow/Akshayparakh98.svg?style=social" target="_blank" />
  </a>
</p>
<b align="center">
  
## 🏠 [Homepage](https://akshaycrazzy.github.io/YouTubeDownloader-AHK/)

  ### [*Total 1094 domains supported*](https://github.com/AkshayCraZzY/YouTubeDownloader-AHK/blob/master/SupportedSites.md)
  
 </b> 
 
 <p align="center">
    This is a AHK Script for downloading videos and music from YouTube and other websites.
 </p> 
 
 
<p align="center">
     This is basically a GUI wrapper for python based youtube-dl project.
       <img align="center" src="https://raw.githubusercontent.com/AkshayCraZzY/YouTubeDownloader-AHK/master/Media/git-gif3.gif"/>
       <a href="https://akshaycrazzy.github.io/YouTubeDownloader-AHK/">
       </a>
  
  </p>   
   
# Install

  **STEP 1 :**
 
  [Download AutoHotkey](https://www.autohotkey.com/download/ahk-install.exe) and install it. (Required for running the script)

  **STEP 2 :**
  
  [Download FFmpeg](https://drive.google.com/uc?export=download&id=1jubMVolwxrZYRkVTspM9yyELNke-Mo85) (Required for conversion and combining video and audio of video)
  
  [Download youtube-dl](https://yt-dl.org/latest/youtube-dl.exe) (Required for downloading videos and audio)

  ***Optional -*** [Download phantomjs](https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-2.1.1-windows.zip) (Needed only for webpages which requires native JS extraction) 
  
  
  Copy the code from [YouTubeDL.ahk](https://raw.githubusercontent.com/AkshayCraZzY/YouTubeDownloader-AHK/master/YouTubeDL.ahk)

   ```
    After installing AutoHotkey
  
    1. Create a empty AHK script by right clicking anywhere on Desktop/Any Folder 
      after that select New > AutoHotkey Script
  
    2. Copy the code and paste it into the new script and save it as YouTubeDL.ahk
 ```
 
  **STEP 3:**

  Copy all 3 files in same folder (Script won't work if these files are not in same folder)
   ```
    YouTubeDL.ahk
    FFmpeg.exe
    youtube-dl.exe
    phantomjs.exe (Optional)
   ```

# Usage

**STEP 1 :**
 ```
  Double click on the YouTubeDL.ahk
  ```
 
**STEP 2 :**
```
  Enter the video URL to download and select between video/audio.
  ```
 
 **STEP 3:** 
```
  Select the output folder to save the video and check if you want Fast Mode 
  
  If Fast Mode is checked skip STEP 4 
  ```
  ***Fast Mode - Skips the metadata import process required for choosing the quality for download instead it always downloads best quality avaiable (Works only for Youtube).***
 
**STEP 4:** 
```
  Wait for video parsing process to complete and select the quality in which you want to download. 
  ```


# Author

👤 **Akshay Parakh**

* Twitter: [@Akshayparakh98](https://twitter.com/Akshayparakh98)
* Github: [@AkshayCraZzY](https://github.com/AkshayCraZzY)

# Built With

* Extractor Used - [youtube-dl](https://github.com/ytdl-org/youtube-dl)
* Language Used - [AutoHotkey](https://www.autohotkey.com/)
* Editor Used - [SciTE4AHK](https://github.com/fincs/SciTE4AutoHotkey)
* Tester Used - [CodeQuickTester](https://github.com/G33kDude/CodeQuickTester/)
# 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://twitter.com/Akshayparakh98).

# Show your support

Give a ⭐️ if this project helped you!

<a href="https://www.patreon.com/akshaycrazzy">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

# 📝 License

Copyright © 2020 [Akshay Parakh](https://github.com/AkshayCraZzY).<br />
This project is [MIT](https://github.com/AkshayCraZzY/YouTubeDownloader-AHK/blob/master/LICENSE.md) licensed.
