# ForgeBase local update channel

This repository contains packaged binaries and signed update metadata. Application source remains private. No publisher private key, customer key or user database belongs here.

Initial version 0.7.0 is an evaluation build. Native installation and a complete installed-update cycle have not yet been accepted. Read each release and platform receipt before use. Windows installers are unsigned; Mac apps are not notarized.

Each signed pointer is at channels/local/latest-OS-CPU.json on main. Update clients verify the pinned Ed25519 key and archive SHA-256. Archives are immutable versioned release assets. Per-platform pointers advance independently after assets are uploaded. A GitHub pre-release label does not disable this explicit local evaluation channel.

Customers do not need a GitHub login. Software license activation is planned separately and is not enforced in the evaluation build.
