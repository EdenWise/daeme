Basic, extremely-simple, scripts for Digital Audio Extraction (i.e. "ripping").

(_These scripts are basic wrappers, primary thanks here goes to the RipIT developer(s).)

### How they look

`daeme` is for MP3s (pronounced _day-m_):

![](/path/to/image)

`daefe` for MP4s:

!(](/path/to/image)

### Settings

Some settings are better in configuration file as their values won't change. What I use:

``` bash
faacopt=-s
---
dirtemplate="${artist} — ${album}"
---
playlist=0
---
eject=1
```
