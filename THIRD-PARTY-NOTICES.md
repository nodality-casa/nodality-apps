# Third-party notices

Generated for each image at build time from its own package database; the list is in each image at
`/licenses/PACKAGES.txt`. Do not edit by hand.
Components under GPL or similar carry a written source offer in the image's /licenses folder.

## App icons (blue ring)
- Glyphs from Material Symbols (outlined): hub, shield, monitor_heart. Copyright Google LLC, Apache License 2.0.
  Source: https://github.com/google/material-design-icons at commit 737e3324305806514d7909874fa1818ae1808232
  (symbols/web/<name>/materialsymbolsoutlined/<name>_24px.svg). Path data unchanged; recoloured and scaled, and placed inside our own ring.
  Licence text: LICENSES/Apache-2.0.txt. Not endorsed by Google.

## Container base image (app images)
- Version 0.1.0 of Nodality, Node Heartbeat and Node Guard: Alpine Linux 3.22, pinned by digest
  sha256:5291449c3df73caf6ed85e649dec1b9e818b39a5d8c871e97afc13e9cd5e8fa8.
  Added packages: bash (GPL-3.0-or-later), curl, jq (MIT), python3 (PSF-2.0), openssl (Apache-2.0), openssh-client
  (BSD and others), tzdata, and keepalived (GPL-2.0-only; Node Heartbeat only), with their dependencies. All are the
  distribution's packages, used unmodified and not linked with our code.
  The package list, licences, source locations and the written source offer are in each image at /licenses/PACKAGES.txt
  and /licenses/SOURCE-OFFER.md. To request source: support@nodality.casa, subject "Source code request".
- Versions 0.0.1 to 0.0.3 of the test placeholder: Alpine Linux 3.20.10, pinned by digest
  sha256:d9e853e87e55526f6b2917df91a2115c36dd7c696a35be12163d44e6e2a4b6bc. Contains GPL-2.0 packages (BusyBox and
  others), used unmodified.
