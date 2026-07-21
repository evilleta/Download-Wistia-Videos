# Download Wistia Videos

A straightforward utility/script designed to bypass front-end player restrictions and extract direct download links for Wistia videos embedded on websites. This tool is perfect for offline viewing, archiving course materials, or saving presentations that use the Wistia hosting platform.

---

## 🛡️ Key Features

* **Bypass Restrictions:** Easily get around disabled right-click menus and custom player controls that prevent native downloading.
* **Direct MP4 Extraction:** Extracts the raw `.mp4` video files directly from Wistia's content delivery network (CDN).
* **Multiple Resolutions:** Depending on the script parameters, you can often select from different available video qualities (e.g., 720p, 1080p).
* **Lightweight:** No bulky software installations required; can be executed via browser developer tools or a simple script environment.

---

## 🚀 How to Use

*(Note: Instructions may vary slightly based on the exact script file you are using in this repository. Below is the general workflow.)*

1. **Find the Wistia Video ID:**
   * Navigate to the webpage containing the embedded Wistia video.
   * Right-click the page and select **Inspect** (or press `Ctrl+Shift+I` / `Cmd+Option+I`).
   * Search the DOM (using `Ctrl+F`) for `wistia_async_` or `wvideo=`. The 10-character alphanumeric string following these tags is the Video ID (e.g., `abc123def4`).

2. **Run the Extraction:**
   * Open the provided script from this repository.
   * Replace the placeholder ID in the code with the actual Video ID you found.
   * Execute the script or construct the direct Wistia CDN URL (e.g., `https://fast.wistia.net/embed/iframe/{VIDEO_ID}`).

3. **Download the File:**
   * Once the raw `.mp4` URL is generated, open it in a new browser tab.
   * Right-click the video and select **Save Video As...** to download it to your local machine.

---

## ⚠️ Disclaimer & Fair Use

**This tool is strictly for educational purposes and personal offline viewing.**
Please respect copyright laws and the intellectual property of content creators. Do not use this tool to download, distribute, or monetize copyrighted material without explicit permission from the rightful owner. The author assumes no liability for the misuse of this script.

---

## 👨‍💻 Author & Credits

* **Developer:** Erick Villeta
* **Website:** [https://ericksonvilleta.com](https://ericksonvilleta.com)

## 📄 License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute the code for your own educational projects.
