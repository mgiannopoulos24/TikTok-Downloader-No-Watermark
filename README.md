# TikTok-Downloader-No-Watermark
A simple Python script to use a website in order to download TikToks without a watermark.

This script is super simple and very basic, it does not do much and it is useless using it on its own. You can just go to the website itself and download the TikToks from there.

I made this as a base to anyone trying to make a bot or a GUI or something, so feel free to use this if you cannot find anything better. Of course there are ways you can download TikToks without using a specific website, but it is way more complicated than this.

This script can be easily editted and made so it downloads many TikTok videos instead of one at a time.

To use this just run it and input your TikTok URL, it should work with the larger ones as well.

## UPDATE

Use **TikTok-Downloader-v2** instead and do not install the requirements!

Simply run the script and input the TikTok URL!

If you want to import this into another script, you could simply do: 

```py
import TikTokDownloaderv2 as tiktok_dl
tiktok_dl.download_tiktok(url)
```

If you like my work, I will be uploading a Reddit Post (including videos) downloader, an Instagram Post (except stories) downloader and maybe others when I document them, so stay tuned!

<<<<<<< HEAD
## UPDATE

Added a simple GUI.

To use **TikTok-Downloader-v3** you need to enter the following command: `pip install -r requirements.txt`

Then to run the program enter: `python3 .\TikTokDownloaderv3.py`

=======

## Update v3

Use **TikTok-Downloader-v3**. In order to install the requirements you will need to use `pip install -r requirements.txt`.

To run it you need to type the command `python3 TikTokDownloaderv3.py` and hit Enter.

### Key Improvements
- **Error Handling**: Now handles HTTP errors and JSON parsing errors gracefully.
- **Modularity**: Split the functionality into smaller, more focused functions for better readability and maintainability.
- **URL Validation**: Consolidated URL validation logic to handle both mobile and web URLs more effectively.

*The program may not work because the owner may have unsubscribed from Heroku.*
>>>>>>> 085a52af76d0afb18ff0488847c608aee96f2c7e
