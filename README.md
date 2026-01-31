# Jellyfin Plugin Repository

Custom Jellyfin plugin repository containing Xtream-related plugins.

## Repository URL

Add this repository to Jellyfin:

```
https://firestaerter3.github.io/jellyfin-plugin-repo/manifest.json
```

## Available Plugins

### Xtream Library
Sync Xtream VOD and Series content to native Jellyfin libraries via STRM files.

- **Category**: General
- **Repository**: [Jellyfin-Xtream-Library](https://github.com/firestaerter3/Jellyfin-Xtream-Library)
- Works with all clients including Swiftfin
- Creates native library items with TMDB/TVDb metadata

### Jellyfin Xtream (Flat View)
Stream Live IPTV, Video On-Demand, and Series from an Xtream-compatible server.

- **Category**: LiveTV
- **Repository**: [Jellyfin.Xtream](https://github.com/firestaerter3/Jellyfin.Xtream)
- Flat view browsing, eager caching, TVDb/TMDB artwork

## Installation

1. Open Jellyfin admin dashboard
2. Go to **Plugins** → **Repositories** tab
3. Click **+** to add a repository
4. Enter:
   - **Name**: `Xtream Plugins`
   - **URL**: `https://firestaerter3.github.io/jellyfin-plugin-repo/manifest.json`
5. Click **Save**
6. Go to **Catalog** tab and install desired plugins
