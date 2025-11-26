# <img src="https://watchtogetherplayer.com/icons/logo.png" width="40"> Watch Together

## Ever wanted to remotely watch something together with your friends, family, or small community?

This is a way to do it.

The goal of this project is to allow people in multiple locations to watch any media file together **in sync**.  
Currently only on desktops. (Windows, Linux, Mac)  
(Mobile/TV applicaiton are possible)

This is a **self-hosted standalone client/server** applicaiton written in C# using [Avalonia UI](https://avaloniaui.net/) and [VLC](https://www.videolan.org/). (Not web-based)  
The source code is not public.

The documentation and a more verbose description and reasoning ([Why not Plex/Jellyfin?](https://docs.watchtogetherplayer.com/reasoning.html), [Where is the source code?](https://docs.watchtogetherplayer.com/open_source.html)):  
https://docs.watchtogetherplayer.com/introduction.html

If you want to chat about the project, there is a [Discord](https://discord.gg/W9EkTF83cj) server for it.  
(Opening an issue here is also possible, but it might take a bit longer for me to respond)

The project is under development, more features or updates are coming.  
This is a one-man, part-time operation so the speed of change won't be very fast, there are sometimes longer times with no updates.

The project has not yet seen any big stress tests with tens or hundreds of users connecting over the internet to see how it performs.

## Current Features
- Invite system- Create invitations for users to join your server.
- Watch groups - Creation and joining of a synchronized group of users, watching the same media.
- Local media - Possible to watch local media files without a server.
- Custom subtitles - Option to add a [custom subtitle file](subtitle_and_audio_tracks.md#custom-subtitle-file) to currently playing media.
- Server-side additional subtitles - Possibility to upload subtitle files.
- Subtitle and audio track choice - Possible to choose for the entire group on play.
- Server media - The server holds your media files.
- Server media library - Movies and Series with seasons, collections of media files with a poster image and title.
- Client playlist - local play list, you can queue available media from the server to play. (You can queue an entire series season)
- Local media sharing - It is possible to share a local file with the server. (Currently no access control)
- Remote media sharing - Downloading media from external websites.
- Admin panel - The place where server owners and administrators decide who has access and what they can watch.
- Play time tracking - When you stop watching and return later, you get the option to continue where you left off. (Server media only)

## Big features to look forward to
- Preloading - When you expect a larger group of people, a regular common gigabit connection probably won't be enough to stream to everyone at once. Thus there needs to be a way to preload files in advance and only keep people in-sync while watching.

## What does it look like

![image1](https://docs.watchtogetherplayer.com/images/player.png)  
![image2](https://docs.watchtogetherplayer.com/images/media_tab.png)  
![image3](https://docs.watchtogetherplayer.com/images/group_tab_create.png)  
![image3](https://docs.watchtogetherplayer.com/images/group_user_options.png)  

More in the gallery:  
https://docs.watchtogetherplayer.com/gallery.html
