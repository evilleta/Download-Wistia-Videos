1. **Download and install** the [Wistia Video Downloader](https://chromewebstore.google.com/detail/wistia-video-downloader/acbiaofoeebeinacmcknopaikmecdehl) Chrome browser extension.
2. **Right-click** on the playing video and select **Copy link**.
3. **Find the Wistia video ID** in the copied link (e.g., `wvideo=tra6gsm6rl`).
   * *Alternative way:* Look for `hashedId=tra6gsm6rl` in the page source.
4. **Load** `http://fast.wistia.net/embed/iframe/` + `[video ID]` in your browser's address bar.
5. **Look for** `"type":"original"` in the page source and copy the URL from the next line. 
   * *Example:* `"url":"http://embed.wistia.com/deliveries/129720d1762175bcd8e06dcab926ec76ad38ff00.bin"`
   * *Alternative way:* Look for `"type":"hd_mp4_video"`.
6. **Download the video** from the extracted URL, ensuring you save it with an `.mp4` extension instead of `.bin`.