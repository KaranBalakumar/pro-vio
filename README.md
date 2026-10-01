# Uncertainty-Aware Multi-Spectral Inertial Odometry for Extreme Environments

Static project page: https://karanbalakumar.github.io/pro-vio/

The page includes the completed A0 research poster and the supplied RGB–thermal SubT screencast from 0:01 to 4:00 (3:59 total). Google Sans and the red/white palette match the poster. The M, S and O initials are black in the website title. All fonts and media are served locally; no third-party embeds are required.

- `index.html` and `assets/site.css`: responsive project page.
- `assets/video/run_12_rgb_thermal_001_400.mp4`: 1920 × 1080 H.264 video, trimmed to 239 seconds with the MP4 index at the start for streaming.
- `assets/video/preview.jpg`: a frame extracted from the source recording.
- `assets/poster/mso_poster.pdf`: the completed poster, including a large upper-right QR code that opens this page.
- `assets/poster/mso_poster_preview.png`: poster preview used on mobile and for link sharing.
- `assets/fonts/`: locally bundled Google Sans webfonts and OFL license.

Preview with `python3 -m http.server 8765` from this directory, then open http://localhost:8765/ . All asset links are relative and work under the `/pro-vio/` GitHub Pages path. GitHub Pages publishes this repository's main branch.

The recording is a separate demonstration; the poster's reported benchmarks and recorded optimization trace retain their original provenance. `media-provenance.json` records source hashes, the trim/encode settings and the exact poster PDF hash.
