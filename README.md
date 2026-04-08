# JSPF-to-XSPF-Converter
Simple Listenbrainz.org jspf playlist converter for Tidal XSPF Playlists made with AI assist

# Features

* Converts JSPF to XFPF with the same name as original
* Simplify Playlist Title to Weekly Exploration 2026-04-06 or Weekly Jams 2026-04-06
* The Title of other lists remains original eq. 'LB Radio for tags progressive metal, progessive on hard mode'

# Setup

Clone repository
```
git clone https://github.com/boozeman/JSPF-to-XSPF-Converter.git
```

Adjust playlist-converter/dockerfile and docker-compose suitable for your needs

```
docker compose build playlist-converter
docker compose up playlist-converter -d
```

# Usage

- Go to your listenbrains.org Created for you page
- Select Weekly Jams or Weekly Exploration / Use LB https://listenbrainz.org/explore/lb-radio/ Radio with your options
- Use that cog to export playlist as jspf / Options > Export as JSPF
- Use this converter (http://your_hostname:3003) to convert jspf to xspf (File generated to user Downloads dir with original name)
- Go to your Tidal playlists and press that ... -> Transfer your music
- Approve and Connect
- Drop / Select your xspf-file
- Press Transfer to Tidal
- Press Complete
- PROFIT!


# DISCLAIMER 

Rear Lights Warranty is on!
