# Publishing checklist

## 1. Repository

- **Name:** `relay`
- **Description:** Media downloader and queue - YouTube, SoundCloud, playlists, 4K video, FLAC audio.
- **Topics:** `youtube-downloader media-downloader yt-dlp ffmpeg python cli playlist`
- **Visibility:** public

## 2. First push

```bash
git init
git add .
git commit -m "Relay 2.2.0 - initial release"
git branch -M main
git remote add origin https://github.com/<you>/relay.git
git push -u origin main
```

## 3. Release

1. Draft a release tagged `v2.2.0`.
2. Title: `Relay 2.2.0`.
3. Body: copy the top entry from `CHANGELOG.md`.
4. Attach the build archive.
5. Publish.

## 4. Settings

| Setting | Value |
| --- | --- |
| Website | the download folder |
| Discussions | enabled |
| Issues | enabled |
| Social preview | export `assets/hero.svg` at 1280x640 |

## 5. First week

- [ ] Release + pin
- [ ] Push a small follow-up commit
- [ ] Reply to every issue within 24 h
- [ ] Publish one screenshot or clip
- [ ] Ship 2.2.0 patch with a visible fix

Keep a 2-3 day commit cadence. Consistency beats volume.