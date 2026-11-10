# Jonathan Yandel · Composer Portfolio

This single-page site uses plain HTML, CSS, and JavaScript. Edit `content.js` to update track metadata and links.

## Preview locally

Open `index.html` directly in your browser. You can also run a local-only server from this folder.

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Visit `http://127.0.0.1:8000/`. Press Ctrl+C to stop the server.

## Replace the placeholders

- **Tracks.** In `content.js`, edit the `tracks` list to change the order, titles, and descriptions. Set `soundcloudUrl` to a public SoundCloud track permalink for each cleared composition. The custom card uses the cover from SoundCloud’s oEmbed metadata when available. Set `artwork` to a local image path for fallback, or leave it blank for the music note icon. The `artworkAlt` text and `duration` are optional. Select the play icon on **The Song of Makara** to open the native SoundCloud player under its custom card. SoundCloud playback needs internet access.
- **Credits.** Add official project or video URLs to `creditLinks` in `content.js`. Blank entries show plain titles.
- **Profile photo.** Replace `assets/portrait.webp` to update the About photo. Match the image’s dimensions and alt text in `index.html` and adjust `object-position` in `styles.css` as needed. The portrait displays in a 4:5 frame, up to 180 pixels wide.
- **Contact.** In `content.js`, fill in `contactEmail` and add your profile URLs to `socialLinks`. Blank entries keep their controls inactive.
- **Design.** Colors and page gutters are defined in `styles.css`. Replace `assets/hero.jpg` to change the backdrop.

## Artwork

The hero backdrop was created with Codex’s built-in ImageGen tool. The local fallback for **The Song of Makara** comes from that track’s SoundCloud artwork.

<details>
<summary>ImageGen prompt</summary>

> Stylized-concept web hero background, an original dark cinematic widescreen landscape panorama, 3:1 frame, photoreal fantasy film still. Jagged layered slate mountain peaks and rolling mist in a desaturated charcoal-blue night valley. The main ridge rises in the center-right, with a pale gibbous moon in the upper right behind thin haze, and subtle warm rock highlights. Left third is low-detail deep charcoal fog with naturally dark negative space for website text. Rich fine-grain rock texture and depth, low-key exposure and restrained moonlight, grounded rather than fantastical. Darkened bottom edge. Edge-to-edge landscape art only. No text, interface, logo, figures, or borders.

</details>
