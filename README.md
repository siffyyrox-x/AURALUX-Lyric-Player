AURALUX
AURALUX is a single-file, frontend-only music and synchronized lyric player designed for GitHub Pages.
Features
- Paste a YouTube URL and play it through the official YouTube embedded player
- Animated artwork, playback visualizer, lighting and motion effects
- Synchronized LRC lyric playback
- Import .lrc files
- Paste plain lyrics and create timing with Tap Sync
- Auto-fit plain lyrics across the track duration
- Click any lyric line to seek to that timestamp
- Local MP3, WAV and other browser-supported audio playback
- Recent YouTube history stored with localStorage
- Per-video lyric sessions stored locally in the browser
- Export synchronized lyrics as .lrc
- Export the current project/session as .json
- Download a locally loaded audio file
- Responsive desktop and mobile design
- Reduced-motion accessibility support
- No backend, database, account, API key, framework or build step
Deployment
1. Put index.html in the root of a GitHub repository.
2. Open Settings > Pages.
3. Choose Deploy from a branch.
4. Select main and /root.
5. Save.
Note
YouTube media is played through YouTube's official embedded player. A static frontend cannot and should not extract or download YouTube audio. Lyrics are supplied by the user through LRC import, pasted text or Tap Sync.
P.S.
This project was built through AI-assisted vibe coding, guided by my own creativity, ideas, and basic understanding of development. It was an experimental project focused on exploring what’s possible through AI-powered development.
