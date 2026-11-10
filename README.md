# @USPoliticsAlert screenshot archive

Public archive of screenshots of X posts from accounts monitored by [@USPoliticsAlert](https://x.com/USPoliticsAlert), maintained by PlatformAlerts.

Each screenshot is published in its own dated folder under `captures/`, containing:

- `screenshot.png`: the original PNG delivered by Microlink, without subsequent image editing or recompression.
- `metadata.json`: source, UTC timestamps, capture configuration, image dimensions and SHA-256 fingerprint.
- `README.md`: a human-readable explanation of how and when that image was obtained.

The folder date records completion of local archiving. Post publication, screenshot request and record preparation timestamps are recorded separately. Microlink may return a cached image; when its exact rendering time or cache status is unavailable, these fields explicitly remain unknown. The first publication of each folder is recorded in GitHub's commit history.

X popup/dialog layers are hidden before capture. Screenshots may include surrounding posts and replies, and content outside the viewport may be omitted. Videos appear as still images. Records for captures predating this publisher explicitly identify configuration reconstructed from the collector version in use.

Automated publications add new folders and preserve previous captures. Each update publishes the PNG, metadata and README together. The SHA-256 fingerprint verifies image integrity; it does not independently certify capture time.
