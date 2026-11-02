
# EgoCenter: Bring Your Data Back Home

EgoCenter is an umbrella project that unites several tools around a single goal: putting your data back where it belongs, with you.

It was born from the need to break free from commercial cloud services, which too often use their users’ content to train models without telling them. EgoCenter is a headless solution (no monitor or local interface, fully managed over the network) for building your own media server and personal cloud. It starts simple and can grow into far more advanced setups as your needs evolve.

## EgOS: Simple and Clean

A streamlined system for anyone who wants a secure home for photos, videos and media, with no complications.

### What’s included

Storage management utilities
Jellyfin: your own media server for movies, TV shows and music
Immich: backup and gallery for your photos and videos
Just these two apps, nothing unnecessary

### How it works

An internet connection is required only for the first two boots
Once set up, you can disconnect it from the outside world entirely: your data stays safe, beyond the reach of any exposure

### Limitations

Only Jellyfin and Immich are included. To add more apps, you need EgoBuilder.

While offline, features that depend on online services are unavailable. This mainly affects Jellyfin: no automatic download of metadata, posters or subtitles
Without internet, it receives no updates. To install them, reconnect it temporarily

## EgoBuilder: For Those Who Want More

A Docker container with a web app that guides you through building your own custom EgOS: choose your apps, and EgoBuilder preloads them into the ISO image.

### What it lets you do

Build a tailor-made EgOS ISO image
Preload any Dockerized app into the image
Configure everything from the web app instead of by hand

### Limitations

Requires some extra expertise: you need to know how to run a Docker container and be familiar with the apps you want to add
Compatibility, configuration and offline operation of added apps depend on the apps themselves

## EgoAppCenter: Under Construction

The next piece of the ecosystem. Work in progress, more to come soon.
