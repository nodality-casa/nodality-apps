# Nodality apps

Home Assistant apps for Nodality: failover for Home Assistant.

To install, add this repository in Home Assistant (Settings > Apps > App store > Repositories) using the address
`https://github.com/nodality-casa/nodality-apps`.

| App | What it does |
|---|---|
| **Nodality** | The agent. Pairs this Home Assistant with the Nodality Cloud Console from the panel in the sidebar, runs the instance's scheduled checks and does only the actions Nodality allows. Install this one first. |
| **Node Heartbeat** | Moves the shared address between your two instances if the primary stops. Installed and set up by Nodality when you pair. |
| **Node Guard** | A safety net that makes sure Home Assistant starts again after a restart and that only one instance runs your home. Installed and set up by Nodality when you pair. |

**Status: version 0.1.0, an early release.** You need a Nodality account and subscription to use it; the apps do nothing
useful on their own.

This repository holds only the app manifests, icons, licence and third-party notices. The app images are published to the
Nodality container registry (`ghcr.io/nodality-casa`). Each image carries its licences, a package list and a written
source offer for the open-source packages it contains, in `/licenses`.

Nodality is developed and supported by 808 Technology Limited. Nodality is independent and is not made, endorsed or
certified by the Home Assistant project, Nabu Casa or the Open Home Foundation. Home Assistant is a trade mark of its
owner; it is named here only to say what Nodality works with.

The software is proprietary and licensed under the Nodality Terms (see LICENSE). Third-party parts keep their own licences
(see THIRD-PARTY-NOTICES.md and each image's /licenses folder). The licence protects the code; the scripts in the images are
readable by customers and that is expected.

Support: support@nodality.casa
