# Kodirepo-LiveTV - CZ/SK

Kodi addon repository for Czech and Slovak TV channels with EPG support.

## Supported Kodi Versions
- **Kodi 20 Nexus** (primary)
- **Kodi 21 Omega** (compatible)

## Included Addons

### plugin.video.livetv.czsk
Main addon for watching Czech and Slovak TV channels.

**Features:**
- Live TV streaming for CZ/SK channels
- EPG (Electronic Program Guide) support - 7 days
- Catch-up support for selected channels (CT, RTVS)
- Integration with PVR IPTV Simple Client
- Standalone mode (direct from addon)

**Supported Channels:**

| Country | Provider | Channels |
|---------|----------|----------|
| CZ | Ceska Televize | CT1, CT2, CT24, CT Sport, CT:D/art |
| CZ | Prima | Prima, Cool, Max, Krimi, Love, Zoom, Star, Show, CNN Prima |
| CZ | Nova | Nova, Cinema, Sport 1, Sport 2 |
| CZ | Barrandov | TV Barrandov, Kino Barrandov |
| CZ | Music | Ocko, Ocko Expres, Ocko Star, Retro Music |
| SK | RTVS | Jednotka, Dvojka, :24, RTVS Sport |
| SK | JOJ | JOJ, Plus, WAU, Family, 24, Cinema, Sport |
| SK | JOJ | CS Film, CS History, CS Mystery |
| SK | News | TA3 |

**Catch-up Support:**
- Ceska Televize (CT1, CT2, CT24, CT Sport, CT:D/art) - Full 7-day catch-up
- RTVS (Jednotka, Dvojka, :24, Sport) - Limited catch-up (own productions only)

## Installation

### Method 1: Add Repository Source
1. Open Kodi
2. Go to **Settings** > **File Manager** > **Add Source**
3. Enter URL: `https://cratos38.github.io/kodirepo-livetv-czsk/`
4. Name it: `LiveTV CZ/SK`
5. Go to **Add-ons** > **Install from zip file** > **LiveTV CZ/SK**
6. Select `repository.livetv.czsk-x.x.x.zip`
7. Install addons from the repository

### Method 2: Direct ZIP Install
Download the addon ZIP and install via **Add-ons** > **Install from zip file**

## Repository Structure
```
kodirepo-livetv-czsk/
├── docs/
│   ├── addons.xml
│   ├── addons.xml.md5
│   ├── index.html
│   ├── plugin.video.livetv.czsk/
│   │   ├── addon.xml
│   │   └── plugin.video.livetv.czsk-x.x.x.zip
│   └── repository.livetv.czsk/
│       ├── addon.xml
│       └── repository.livetv.czsk-x.x.x.zip
└── README.md
```

## Development

### Building the repository
```bash
python3 create_repository.py
```

## Credits
- **Author**: cratos38
- **Based on**: freeview.sk by cache-sk
- **Data sources**: iptv-org, iptv-epg.org

## License
AGPL-3.0

## Links
- [GitHub Repository](https://github.com/cratos38/kodirepo-livetv-czsk)
- [Issues](https://github.com/cratos38/kodirepo-livetv-czsk/issues)
