Hanash is a general purpose multi-connections download manager based on python, 
it downloads general files, also support downloading videos, and playlists from youtube. <br>
Developed in Python, based on "pyCuRL/curl", "youtube_dl", and designed by "PySimpleGUI"


**snapshots**

![main window](https://github.com/Aboghazala/Hanash/blob/master/images/main.PNG)


![downloads_tab](https://github.com/Aboghazala/Hanash/blob/master/images/downloads.PNG)
![setting_tab](https://github.com/Aboghazala/Hanash/blob/master/images/setting.PNG)
![d_window](https://github.com/Aboghazala/Hanash/blob/master/images/d_window.PNG)

example multi-downloading with speed limit of 10 KB/sec as a test

![concurrent windows](https://github.com/Aboghazala/Hanash/blob/master/images/concurrent_windows.PNG)


**-----Requirements -------**
```python
Python 3+
ffmpeg : for merging audio with youtube DASH videos
python packages: pycurl, certifi, PySimpleGUI, mimetypes, pyperclip, plyer, pillow, youtube_dl

```

you can run one line command to install required packages:
```python
python -m pip install pycurl certifi PySimpleGUI mimetypes pyperclip plyer pillow youtube_dl
```

**note for Youtube-dl:** <br>
youtube website changes frequently, if this application failed to retrieve video/playlist data
you should update youtube-dl module https://github.com/ytdl-org/youtube-dl
```
python -m pip install youtube_dl --upgrade
```

**note for pyperclip:** <br>
Pyperclip is a cross-platform Python module for copy and paste clipboard functions. it is being used if you want to monitor clipboard for files urls and it will be processed automatically by Hanash DM.
On Linux, this module makes use of the xclip or xsel commands, which should come with the os. Otherwise run "sudo apt-get install xclip" on Debian like or "sudo pacman -S xclip" on archlinux

**Windows:** <br>
a standalone compressed version available on: https://github.com/Aboghazala/Hanash/tree/master/windows


<br><br>

**Versions change log**: <br>
3.1.0:
1. added functionality to download youtube DASH videos with audio merged using ffmpg <br>

<br><br>

**Future Plans**:
1. use native video library for merging audio and video, will check libav, or possibility with youtube_dl  <br>

<br><br><br>
your feedback is most welcomed by filling an issue on https://github.com/Aboghazala/Hanash <br>
Cheers, <br>
Mahmoud Elshahat, <br>
2019


