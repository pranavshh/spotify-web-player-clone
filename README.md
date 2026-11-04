# spotify-web-player-clone
A static Spotify web player UI clone built with pure HTML and CSS: sidebar library, sticky top bar, hoverable playlist cards, and a fixed bottom music player.

# Spotify Web Player Clone

A front-end clone of the Spotify web player interface, built with plain HTML and CSS. This is a UI practice project. It has no backend and no audio playback.

![Screenshot](assets/screenshot.png)

## Features

- Dark-theme layout with a left sidebar (Home, Search, Your Library) and a scrollable main content area
- Library panel with "Create your first playlist" and "Browse podcasts" prompt cards
- Sticky top navigation with back/forward arrows, Explore Premium, Install App, and a user icon
- Card sections (Recently played, Trending now near you, Featured charts) in a wrapping flex grid
- Hover effects on cards, buttons, and icons
- Fixed bottom music player bar with track info, playback controls, seek bar, and volume slider
- Responsive tweak: some elements hide below 1000px width

## Built With

- HTML5
- CSS3 (Flexbox, sticky/fixed positioning, media queries, transitions)
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/): Montserrat

## Project Structure

```
spotify-web-player-clone/
├── assets/          # Images and icons (cards, player controls, logo)
├── index.html
├── index.css
└── README.md
```

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/pranavshh/spotify-web-player-clone.git
   ```
2. Move into the folder
   ```bash
   cd spotify-web-player-clone
   ```
3. Open `index.html` in your browser, or use the VS Code Live Server extension.

## What I Learned

- Building multi-column layouts with Flexbox
- Using `position: sticky` and `position: fixed` for the top bar and player
- Styling hover and transition effects
- Structuring a larger CSS file for a real-world UI

## Future Improvements

- Add JavaScript for working play/pause, seek, and volume controls
- Make the layout fully responsive for mobile
- Add real playlist data and song switching
- Add a working search bar

## Disclaimer

This is an educational project and is not affiliated with or endorsed by Spotify. All trademarks and images belong to their respective owners.

## Author

**Pranav**, [@pranavshh](https://github.com/pranavshh)
