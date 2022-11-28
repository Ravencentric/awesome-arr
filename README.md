# Awesome *Arr [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> A collection of *Arrs and related stuff.

## Contents
- [Official *Arrs](#official-arrs)
    - [Indexer Manager](#indexer-manager)
    - [Related Resources](#related-resources)
- [*Arr like Apps](#arr-like-apps)
- [Complimenting Apps](#complimenting-apps)
- [*Arr Scripts](#arr-scripts)
- [Bots](#bots)
- [Media Servers](#media-servers)
- [Dashboards](#dashboards)
- [Mobile Apps](#mobile-apps)
- [Unmaintained](#unmaintained)
- [Contribute](#contribute)

## Official *Arrs
These are collection managers for Usenet and BitTorrent users. They can monitor multiple RSS feeds for new content and will grab, sort and rename them. They can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.
- [Lidarr](https://lidarr.audio/) - Lidarr is a music collection manager.
- [Radarr](https://radarr.video/) - Radarr is a movie collection manager.
- [Readarr](https://readarr.com/) - Readarr is an ebook collection manager.
- [Sonarr](https://sonarr.tv/) - Sonarr is a PVR.
- [Whisparr](https://whisparr.com/) - Whisparr is an adult movie collection manager.

### Indexer Manager
- [Prowlarr](https://github.com/prowlarr/prowlarr) - Prowlarr is an indexer manager/proxy built on the popular arr .net/reactjs base stack to integrate with your various PVR apps. Prowlarr supports management of both Torrent Trackers and Usenet Indexers. It integrates seamlessly with Lidarr, Mylar3, Radarr, Readarr, and Sonarr offering complete management of your indexers with no per app Indexer setup required.
- [Jackett](https://github.com/Jackett/Jackett) - API Support for your favorite torrent trackers. An alternative to Prowlarr.

### Related Resources
- [Servarr](https://wiki.servarr.com/) -  The consolidated wiki for Lidarr, Prowlarr, Radarr, Readarr, and Sonarr.
- [TRaSH-Guides](https://trash-guides.info/) - Guides mainly for Sonarr/Radarr/Bazarr and everything related to it.
- [Recyclarr](https://github.com/recyclarr/recyclarr) - Automatically sync TRaSH guides to your Sonarr and Radarr instances.

## *Arr like Apps
These are not directly part of the official *Arr family but they work similarly to an *Arr and serve as an alternative to them.
- [Flexget](https://github.com/Flexget/Flexget) - FlexGet is a multipurpose automation tool for all of your media. Support for torrents, nzbs, podcasts, comics, TV, movies, RSS, HTML, CSV, and more.
- [Medusa](https://pymedusa.com/) - Medusa is an automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic: automatic torrent/nzb searching, downloading, and processing at the qualities you want.
- [Mylar3](https://github.com/mylar3/mylar3) - The python3 version of the automated Comic Book downloader (cbr/cbz) for use with various download clients.
- [SickGear](https://github.com/SickGear/SickGear) - SickGear has proven the most reliable stable TV fork of the great Sick-Beard to fully automate TV enjoyment with innovation.

## Complimenting Apps
- [Autobrr](https://autobrr.com/) - The modern autodl-irssi replacement.
- [Autoscan](https://github.com/Cloudbox/autoscan) - Autoscan replaces the default Plex and Emby behaviour for picking up changes on the file system.
- [Bazarr](https://github.com/morpheus65535/bazarr) - Bazarr is a companion application to Sonarr and Radarr. It manages and downloads subtitles based on your requirements. You define your preferences by TV show or movie and Bazarr takes care of everything for you.
- [FlareSolverr](https://github.com/FlareSolverr/FlareSolverr) - Proxy server to bypass Cloudflare protection.
- [Flemmarr](https://github.com/Flemmarr/Flemmarr) - Flemmarr makes it easy to automate configuration for your -arr apps.
- [Gclone](https://github.com/l3v11/gclone) - A rclone mod with auto SA rotation.
- [Jellyseerr](https://github.com/Fallenbagel/jellyseerr) - Fork of overseerr for jellyfin support.
- [Monitorr](https://github.com/Monitorr/Monitorr) - Monitorr is a self-hosted PHP web app that monitors the status of local and remote network services, websites, and applications.
- [Notifiarr](https://notifiarr.com/) - Discord notification system.
- [Ombi](https://github.com/Ombi-app/Ombi) - Ombi is a self-hosted web application that automatically gives your shared Plex or Emby users the ability to request content by themselves! Ombi can be linked to multiple TV Show and Movie DVR tools to create a seamless end-to-end experience for your users.
- [Omegabrr](https://github.com/autobrr/omegabrr) - Transform monitored shows and movies from the arrs into autobrr filters.
- [Overseerr](https://overseerr.dev/) - Request management and media discovery tool for the Plex ecosystem.
- [Plex Meta Manager](https://github.com/meisnate12/Plex-Meta-Manager) - Plex Meta Manager is an open source Python 3 project that has been designed to ease the creation and maintenance of metadata, collections, and playlists within a Plex Media Server.
- [Rclone](https://rclone.org/) - Rclone is a command-line program to manage files on cloud storage.
- [Unpackerr](https://github.com/davidnewhall/unpackerr) - Extracts downloads for Radarr, Sonarr, Lidarr, Readarr - Deletes extracted files after import.
- [Wizarr](https://github.com/Wizarrrr/wizarr) - Wizarr is an automatic user invitation system for Plex.

## *Arr Scripts
- [Collectarr](https://github.com/RiffSphere/Collectarr) - A Python script for checking your Radarr database and setting up collection lists. Also supports "smart" actor lists based on TMDB.
- [Elsewherr](https://github.com/Adman1020/Elsewherr) - See disclaimer on page. See if your movies from Radarr are available on a streaming service, and add a tag against the movie if it is.
- [Excludarr](https://github.com/haijeploeg/excludarr) - Excludarr is a CLI that interacts with Radarr and Sonarr instances. It completely manages you library in Sonarr and Radarr to only consist out of movies and series that are not present on any of the configured streaming providers.
- [Exportarr](https://github.com/onedr0p/exportarr) - This will export metrics gathered from Sonarr, Radarr, Lidarr, or Prowlarr.
- [Ezarr](https://github.com/Luctia/ezarr) - Ezarr aims to make it as easy as possible to setup an entire Servarr/Jackett/BitTorrent/PleX/Jellyfin mediacenter stack using Docker.
- [Just A Bunch Of Starr Scripts](https://github.com/angrycuban13/Just-A-Bunch-Of-Starr-Scripts) - PowerShell scripts for Starr apps.
- [Listrr](https://github.com/TheUltimateC0der/Listrr) - Listrr creates lists for shows and movies based on your filters. The created lists get updated every 24 hours based on your filters, so Listrr will add all new items that match your filters, and will also remove all items that do not match your filter configuration anymore. Supports Sonarr, Radarr, Traktarr and Python-PlexLibrary.
- [Mediarr](https://github.com/l3uddz/mediarr) - CLI tool to add new media to pvr's from the arr suite.
- [Rollarr](https://github.com/TheHumanRobot/Rollarr) - Plex Automatic Pre-roll script with a GUI.
- [Sonarr Episode Name Checker](https://github.com/tronyx/sonarr-episode-name-checker) - Bash and Powershell scripts to check for episodes named "Episode ##" or "TBA".
- [StarrScripts](https://github.com/bakerboy448/StarrScripts) - Misc Scripts for Starr related Apps.
- [Tdarr](https://github.com/HaveAGitGat/Tdarr) - Tdarr - Distributed transcode automation using FFmpeg/HandBrake + Audio/Video library analytics + video health checking.
- [Traktarr](https://github.com/l3uddz/traktarr) - Script to add new series & movies to Sonarr/Radarr based on Trakt lists.
- [Transcoderr](https://github.com/drkno/transcoderr) - A transcoding pipeline designed to normalise file types into a common filetype. Dynamically configurable using plugins allowing highly customisable pipelines to be built.

## Bots
- [Addarr](https://github.com/Waterboy1602/Addarr) - Telegram Bot for adding series/movies to Sonarr/Radarr or for changing the download speed of Transmission/Sabnzbd.
- [Botdarr](https://github.com/shayaantx/botdarr) - Slack/Discord/Telegram/Matrix bot for accessing radarr, sonarr, and lidarr.
- [Doplarr](https://github.com/kiranshila/Doplarr) - An *Arr request bot for Discord.
- [Invitarr](https://github.com/Sleepingpirates/Invitarr) - Invitarr is a chatbot that invites discord users to plex.
- [Membarr](https://github.com/Yoruio/Membarr) - Discord Bot to invite a user to a Plex or Jellyfin server.
- [Searcharr](https://github.com/toddrob99/searcharr) - Sonarr & Radarr Telegram Bot.

## Media Servers
These are not *Arrs but are almost always used along with *Arrs.
- [Emby](https://emby.media/) - Emby Server is a personal media server with apps on just about every device.
- [Jellyfin](https://jellyfin.org/) - Jellyfin is a Free Software Media System that puts you in control of managing and streaming your media. It is an alternative to the proprietary Emby and Plex, to provide media from a dedicated server to end-user devices via multiple apps.
- [Kodi](https://kodi.tv/) - Kodi is a free and open source home theater/media center software and entertainment hub for digital media.
- [Homehost](https://github.com/ridhwaans/homehost) - Homehost is made for streaming your media collection within the home network.
- [Midarr](https://github.com/midarrlabs/midarr-server) - Midarr, the minimal lightweight media server.
- [Oblecto](https://github.com/robinp7720/Oblecto) - Oblecto is a media server, which streams media you already own, and is designed to be at the heart of your entertainment experience.
- [Plex](https://www.plex.tv/) - Plex is a streaming media service and a client–server media player platform, made by Plex, Inc. The Plex Media Server organizes video, audio, and photos from a user's collections and from online services, and streams it to the players.

## Dashboards
These are dashboards for your *Arrs and various other services on your server.
- [Dashy](https://github.com/Lissy93/dashy) - A self-hostable personal dashboard built for you. Includes status-checking, widgets, themes, icon packs, a UI editor and tons more.
- [Flame](https://github.com/pawelmalak/flame) - Flame is self-hosted startpage for your server. Easily manage your apps and bookmarks with built-in editors.
- [Heimdall](https://github.com/linuxserver/Heimdall) - An Application dashboard and launcher.
- [Homepage](https://github.com/benphelps/homepage) - A highly customizable homepage (or startpage / application dashboard) with Docker and service API integration.
- [Homer](https://github.com/bastienwirtz/homer) - A very simple static homepage for your server with offline health check.
- [Organizr](https://github.com/causefx/Organizr) - HTPC/Homelab Services Organizer - Written in PHP.

## Mobile Apps
- [LunaSea](https://github.com/JagandeepBrar/LunaSea) - LunaSea is a fully featured, open source self-hosted controller focused on giving you a seamless experience between all of your self-hosted media software remotely on your devices. LunaSea currently supports Lidarr, Radarr, Sonarr, NZBGet, SABnzbd, Newznab, Indexer Searching, NZBHydra2, Tautulli, and Wake on LAN.
- [nzb360](https://nzb360.com/) - Proprietary and paid alternative to LunaSea. Supports SABnzbd, NZBget, Deluge, Transmission, µTorrent, qBittorrent, rTorrent/ruTorrent, Sonarr, Sick Beard, Radarr, Lidarr, Bazarr, Couchpotato, Headphones, NEWZnab, Jackett, NZBHydra2 and Prowlarr.

## Unmaintained
- [Bobarr](https://github.com/iam4x/bobarr) - The all-in-one alternative for Sonarr, Radarr, Jackett, Transmission, and FlareSolverr with a VPN and running in docker. This is no longer in active development, [author is only accepting PRs](https://github.com/iam4x/bobarr/issues/224#issuecomment-1007031439) for this.  (**Last Commit: Apr 6, 2022**).
- [Bonarr](https://github.com/bonarr/Bonarr) - Bonarr is an independent fork of Radarr reworked for automatically downloading adult movies via Usenet and BitTorrent (**Last Commit: Sep 12, 2017**).
- [Cardigann](https://github.com/cardigann/cardigann) - A proxy server for adding new indexers to Sonarr, SickRage and other media managers (**Last Commit: Apr 26, 2020**).
- [Comandarr](https://github.com/Commandarr/Commandarr) - Comandarr is a bot that will interact with Sonarr, Radarr and Lidarr (**Last Commit: Apr 10, 2017**).
- [Listarr](https://github.com/christophercatt/listarr) - A Trakt.tv list -> Sonarr implementation, emulating the list functionality found within Radarr (**Last Commit: Aug 10, 2020**).
- [Logarr](https://github.com/Monitorr/logarr) - Logarr is a self-hosted PHP web app that consolidates, formats, and displays log and text files for easy analysis and monitoring (**Last Commit: Jun 12, 2018**).
- [Movearr](https://github.com/l3uddz/movearr) - Simple CLI tool to perform various Radarr/Sonarr move functions (**Last Commit:  Dec 27, 2020**).
- [Plexarr](https://github.com/l3uddz/plexarr) - Fix mismatched media in Plex mastered by Sonarr/Radarr (**Last Commit: Jun 13, 2021**).
- [Posterr](https://github.com/petersem/posterr) - A digital poster app for Plex, Sonarr, Radarr, and Readarr (**Last Commit: Nov 5, 2021**).
- [Pulsarr](https://github.com/roboticsound/Pulsarr) - Browser extension (currently Chrome & Firefox) for adding movies to Radarr or Series' to Sonarr while browsing IMDB or TVDB (**Last Commit: May 2, 2018**).
- [Requestrr](https://github.com/darkalfx/requestrr) - Requestrr is a chatbot used to simplify using services like Sonarr/Radarr/Ombi via the use of chat. Current platform is Discord only, but the bot was built around the ideology of quick adaptation for new features as well as new platforms (**Archived, Last Commit: Apr 11, 2022**).
- [Sick-Beard](https://github.com/midgetspy/Sick-Beard) - PVR & episode guide that downloads and manages all your TV shows (**Last Commit: Mar 21, 2016**).
- [Syncarr](https://github.com/syncarr/syncarr) - One/two way sync of Radarr, Sonarr, or Lidarr instances (**Last Commit: Jun 8, 2021**).
- [Timearr](https://github.com/l3uddz/timearr) - Custom Import Script for Sonarr/Radarr/Lidarr to reset the mod-time of imported files (**Last Commit: May 9, 2020**).
- [Trackarr](https://gitlab.com/cloudb0x/trackarr) - Trackarr monitors tracker announce IRC channel, parses the announcements, and forwards those announcements to *Arr PVRs (**Last Commit: Jun 10 2021**).
- [Wantarr](https://github.com/l3uddz/wantarr) - CLI Tool to find wanted media for the *arr suite (**Last Commit: Jul 31, 2020**).

## Contribute
Contributions welcome! Read the [contribution guidelines](https://github.com/Ravencentric/awesome-arr/blob/main/contributing.md) first.
