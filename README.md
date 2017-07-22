Forked from https://lpfm.codeplex.com/ to save this project as codeplex is shutting down.
Written by DanielLarsenNZ and adammhaile.

# LPFM-Last.fm-Scrobbler

LPFM Last.fm Scrobbler is a simple .NET API library for scrobbling to the Last.fm web service. It is designed for desktop, web and mobile applications that target the .NET Framework 4 Client Profile. The library supports the Scrobble, Now Playing, Love / Unlove and Ban / Unban functionality of the Last.fm API version 2.0.

Last.fm is a music taste aggregator for music fans from all over the world. It “scrobbles” the track plays from millions of users to help them share and discover music. The extensive Last.fm API has enabled many third-party integrators to include Last.fm functionality into their mobile, desktop and web-based applications. It is to those integrators that this API is dedicated.

Note: LPFM is not affiliated with Last.fm in any way, apart from being massive fans.

# Things you should know

The LPFM Last.fm Scrobbler API is a Class Library DLL written in C# and targeting the Microsoft .NET Framework 4 (client profile)
It is free and opensource software licensed under The MIT License (MIT)
The API wraps portions of the Last.fm webservice version 2.0
Source includes Unit Test projects and XML documentation of all public classes and members

# Supported API methods

Auth
Auth.getToken
Auth.getSession
Track
Track.updateNowPlaying
Track.scrobble
Track.love
Track.unlove 
Track.ban
Track.unban

# Users

LPFM Last.fm Scrobbler is used by Elpis, a native Pandora radio client for Windows. Thanks to Adam Haile for his contribution to this project.

If you are using LPFM we would love to hear from you - let us know in Discussions.

# LPFM

The LPFM Last.fm Scrobbler library is part of the LPFM project, radio station automation software for low power and pirate radio stations. The Scrobbler portion of LPFM is open-source and free, and more LPFM libraries will be open-source in the future.
