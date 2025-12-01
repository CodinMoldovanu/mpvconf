## MPV Config Studio
![Vibecoded](https://img.shields.io/badge/vibecoded-%234ad5c2?style=for-the-badge&logo=waveform&logoColor=0f1623)

### Usage

- Open `index.html` in your browser (no server or bundler needed).
- Tweak options by section; the preview updates live.
- Add arbitrary mpv lines under **Custom entries**.
- Copy or download the generated `mpv.conf` and drop it into `~/.config/mpv/`.
- Toggle **Load sane defaults** vs **Reset to vanilla** to jump between opinions and stock settings.
- Many common options are exposed with short descriptions (playback, video, audio, subs, UI/OSD, caching, network, screenshots); use Custom for anything niche.
- Explore community scripts via the in-page link to `stax76/awesome-mpv`; install scripts into `~/.config/mpv/scripts/` and any `script-opts` into `~/.config/mpv/script-opts/`.

### Notes

- Values mirror mpv option names; comments in the output explain grouping.
- Clipboard API may require a secure context; if blocked, select the textarea and copy manually.
