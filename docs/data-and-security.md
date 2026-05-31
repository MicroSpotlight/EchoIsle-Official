---
title: Data and Security Notes
description: Technical notes about Echo Isle data storage and network behavior.
permalink: /data-and-security/
---

# Data And Security Notes

This page describes Echo Isle's data, storage, and network behavior in practical terms.

## Local Storage

Echo Isle stores app data locally on your device so the app can remember your listening state.

Local data may include:

- Subscribed shows.
- Lightweight episode lists.
- Podcast search and discovery results.
- Playback progress.
- Playback completion state.
- Playback history.
- Download status.
- Downloaded episode files.
- Feed and image cache.
- User settings.

## Cache

Echo Isle uses local caches to reduce repeated network requests and improve scrolling, artwork loading, feed refreshes, and playback continuity.

Cached data may include RSS responses, cover artwork, show metadata, and episode metadata. Cache entries may be removed by app controls, system storage cleanup, or app deletion.

## Downloads

Downloaded episodes are stored locally for personal offline listening. Removing a download deletes the local copy from the app-managed storage area.

## Network Behavior

Echo Isle may make network requests to:

- Search podcasts through the iTunes Podcast Search API.
- Fetch public RSS feeds from podcast publishers.
- Fetch episode audio from publisher-provided media URLs.
- Fetch cover artwork.
- Retry some failed RSS requests through an HTTPS proxy.

Some podcast feeds or media URLs may use legacy HTTP. Echo Isle may access those URLs because podcast publishers control their own feed and media hosting.

## Sensitive Data

Echo Isle does not require account login, payment information, or profile information in the current version.

Do not post private RSS feed URLs, private episode URLs, authentication tokens, or personal information in public GitHub issues.

## Security Reports

For security-sensitive issues, please read:

- [Security Policy](https://github.com/MicroSpotlight/EchoIsle-Official/security/policy)
