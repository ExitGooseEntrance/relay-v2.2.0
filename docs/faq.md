# FAQ

## Is this legal?

Downloading content you do not own may violate the platform terms and local law. Use it for media you have the right to save.

## Why FFmpeg?

Muxing, transcoding, and subtitle work all run through FFmpeg. Relay ships a setup check.

## Does it support Spotify?

Spotify streams are DRM-protected. Relay reads public metadata and matches it to a downloadable source when one exists.

## Can it resume?

Yes. The queue is stored in SQLite and resumes after a restart.


## Where do I report a bug?

Open an issue with the version, the platform, and the steps to reproduce.
Logs live in `%APPDATA%\Relay\logs`.