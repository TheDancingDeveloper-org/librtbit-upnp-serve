# librtbit-upnp-serve

Simple UPnP MediaServer implementation for the rtbit BitTorrent client.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |

### Depends On

- **librtbit-upnp** (git, v0.1.0) — UPnP port forwarding client
- **librtbit-core** (git, v0.1.0) — core types

## Public API

- `UpnpServer` — UPnP MediaServer with SSDP advertising
- HTTP endpoints for device description, SCPD, control, eventing
- DLNA content browsing for torrent files
