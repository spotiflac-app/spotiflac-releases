# SpotiFLAC downloads

Official website: https://spotiflac.com

This repository hosts SpotiFLAC release packages, public update metadata and
the corresponding versioned source archives. Development is maintained
separately. Each published release includes its license notices and matching
source snapshot.

The first release is being validated. No production download is available yet.
Draft release assets are restricted to maintainers until validation is complete.
The existing website download links remain in place while the site is developed.

## Verify a package

Compare its SHA-256 checksum with `SHA256SUMS.txt` from the same release.
Android production packages use the project-owned release key. Unsigned or
ad-hoc signed desktop and iOS packages are identified in their release notes.

## Source and licenses

Use the source archive attached to the same version as your application.
The source retains the original copyright and third-party notices and the
LGPL-3.0-only license with its incorporated GPL-3.0 terms.

## Updates

The public release feed is
`https://api.github.com/repos/spotiflac-app/spotiflac-releases/releases`.
It remains empty until the first release is published. No GitHub credential is
required or embedded in the application for public release downloads.
