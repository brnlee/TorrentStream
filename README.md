# AniFlow
An all-in-one CLI program to streamline your anime watching experience.

## Features
* Lists ready-to-watch episodes from [qBittorrent](https://www.qbittorrent.org/)
* Plays the episode you want to watch with your video player
* Brings up the [r/anime](https://reddit.com/r/anime/) episode discussion thread
* Updates the status and episode progress on [AniList](https://anilist.co)
* Opens the [AniList](https://anilist.co) entry after the final episode has been watched
* Removes the episode from your system and qBittorrent

## Setup
### Dependencies
```console
pip install -r requirements.txt
```

### qBittorrent
Enable the built-in web server:
1. Go to "Options"
2. Press "Web UI"
3. Enable "Web User Interface (Remote Control)"
4. Set "Port"
5. Set "Username" and "Password"

### Reddit
Create an application on [Reddit](https://reddit.com/prefs/apps/).

### AniList
Create a client on [AniList](https://anilist.co/settings/developer).

### .env
Create a ".env" file in the project root directory with the format of "[.env.sample](.env.sample)" and add the secrets for each service.

## Usage
```console
python aniflow
```

## Platform Support
This script has only been tested on Windows.

