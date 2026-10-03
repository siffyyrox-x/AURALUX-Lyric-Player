AURALUX https://siffyyrox-x.github.io/AURALUX-Lyric-Player/
AURALUX is a cinematic browser music player that turns a pasted YouTube song link into a focused listening experience with automatic synchronized lyrics.
Features
- Paste a YouTube song link and start playback directly
- Automatic track title and artist detection
- Automatic lyrics search through LRCLIB
- Synced lyrics when a timed version is available
- Duration-aware lyric matching to reduce incorrect versions
- Automatic timing fallback when only plain lyrics are available
- Smooth karaoke-style lyric progression and auto-scrolling
- Click any lyric line to seek to that moment in the song
- Original YouTube thumbnail used as the player artwork
- Automatic thumbnail quality fallback so broken artwork is avoided
- Animated player controls, progress tracking and ambient interface effects
- Recent-track history stored locally in the browser
- Responsive desktop and mobile layout
- Reduced-motion accessibility support
- Built with plain HTML, CSS and JavaScript
- No framework, account, database or build process required
How It Works
1. Paste a YouTube song link.
2. AURALUX loads the track through the YouTube player.
3. The track metadata is detected automatically.
4. AURALUX searches for the closest lyric match using title, artist and duration.
5. Synced lyrics follow the music automatically while it plays.
No manual lyric pasting or timing setup is required.
Notes
Lyrics depend on the availability and accuracy of matching data from LRCLIB. If a synchronized version is unavailable but plain lyrics are found, AURALUX creates an automatic timing approximation for playback.
YouTube playback is handled through the official embedded player, while AURALUX provides the surrounding player interface, artwork, lyric synchronization and local listening history.

P.S.
This project was built through AI-assisted vibe coding, guided by my own creativity, ideas, and basic understanding of development. It was an experimental project focused on exploring what’s possible through AI-powered development.
