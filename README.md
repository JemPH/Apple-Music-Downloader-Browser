<p align="center">
  <img src="https://music.apple.com/assets/favicon/favicon-180.png" alt="Logo" />
</p>

<h1 align="center">Apple-Music-Downloader-Browser</h1>

<p align="center">
  <a href="https://t.me/JemPH/"> 
    <img
      src="https://img.shields.io/badge/TELEGRAM-blue.svg?style=for-the-badge&logo=telegram&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
  <a href="https://raw.githubusercontent.com/JemPH/Apple-Music-Downloader-Browser/main/apple-music-downloader.user.js"> 
    <img
      src="https://img.shields.io/badge/TAMPERMONKEY-grey.svg?style=for-the-badge&logo=tampermonkey&logoColor=white&labelColor=000000&logoWidth=20">
   </a>
  <a href="https://phcorner.net/members/jemph.1522390/"> 
    <img
      src="https://img.shields.io/badge/PH-PHCORNER-red.svg?style=for-the-badge&logo=&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
</p>

<p align="center">
  Apple-Music-Downloader-Browser is a browser extension that allows you to download your favorite Apple Music content directly from the web interface.
</p>

<p align="left">
  <img src="https://raw.githubusercontent.com/JemPH/Apple-Music-Downloader-Browser/main/assets/preview-1.png" alt="image"/>
  <img src="https://raw.githubusercontent.com/JemPH/Apple-Music-Downloader-Browser/main/assets/preview-2.png" alt="image"/>
  <img src="https://raw.githubusercontent.com/JemPH/Apple-Music-Downloader-Browser/main/assets/preview-3.png" alt="image"/>
</p>

## Features

- **AAC**: High-quality compressed audio files.
- **ALAC** (coming soon): Lossless audio files for audiophiles.
- **Dolby Atmos** (coming soon): Immersive sound experience with spatial audio.
- **Music Videos** (coming soon): Download your favorite music videos from Apple Music.
- **Email and Password** (planned): Future updates will include support for using email and password credentials for accessing ALAC and Dolby Atmos features. This feature is not yet implemented but is planned for future updates.

## Installation
   Install the [script](https://raw.githubusercontent.com/JemPH/Apple-Music-Downloader-Browser/main/apple-music-downloader.user.js) in your userscript manager. The script requires subscription in order to download files.

## Usage
  Just activate and install the script in Tampermonkey. The script should automatically run (as shown in the image preview above). Refresh the page if it doesn't work.

### Usage of `media-user-token`
To operate effectively, our extension requires access to certain resources on `music.apple.com`. Specifically, we use the `media-user-token` to authenticate and interact with Apple Music's web interface. Here’s how we handle it:

- **Purpose:** The `media-user-token` is used solely to facilitate the download of media content from Apple Music and is necessary for the functionality of the extension.
- **Scope:** We only access the `media-user-token` on `music.apple.com` and do not use it for any other purpose or share it with third parties.
- **Security:** We take precautions to ensure that the `media-user-token` is handled securely and is never exposed or misused.

## Code Obfuscation
### Why is the Code Obfuscated?
The source code in this repository has been obfuscated to:
- **Prevent Unauthorized Modifications:** Maintain the integrity of the code and prevent unauthorized changes.
- **Preserve Competitive Advantage:** Keep certain implementation details confidential.
- **Respect for API Limits:** Avoiding abuse of interactions with our API backend server to ensure that usage remains within limits and does not cause undue strain on the servers.

## Contact Us
If you have any questions, concerns, or need further clarification about the obfuscated code or any other aspect of the project, please contact me [here](https://t.me/JemPH). I am here to help and provide any additional information you may need.


<p align="left">
  <a href="https://ko-fi.com/O4O3D65S3">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="ko-fi" />
  </a>
</p>
