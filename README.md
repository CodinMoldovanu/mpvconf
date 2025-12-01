## MPV Config Studio

Lightweight, build-free web app for crafting `mpv.conf` with sensible presets and instant preview.

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
