# ORCHAI — releases

This repository holds only the signed packages of **ORCHAI Desktop** and the manifest the app
reads to offer updates. The source is not here.

## Install

Download the `.dmg` of the latest release, open it and drag ORCHAI to Applications. The app is
signed with a Developer ID and notarized by Apple; it runs on Macs with Apple Silicon or Intel
(macOS 11 or later). Windows comes later.

## Updates

ORCHAI looks for a newer version at most once a day, and when you choose *Check for updates* in
Settings → About. It downloads nothing until you choose *Install and restart*, and it installs a
package only when its signature verifies against the key built into the app. You can turn the
daily check off in the same place.

What the check sends: one request for `latest.json` from this repository — nothing about you.
See [PRIVACY.md](PRIVACY.md).

## Licence

ORCHAI is in beta under the [ORCHAI Beta License](LICENSE): free for personal use; business use
needs a commercial licence.
