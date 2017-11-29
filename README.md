# Harmonize
Personal song management done right.

You have a right to your music, and harmonize is the platform that will allow you to
organize it effectively. Harmonize helps you sync all your songs between all your 
devices, and couples rich metadata with quckly customizable filters to allow elaborate
playlist creation.

# Note
Harmonize is a *work in progress*, this means that breaking changes may be made often
and may produce Ill effects if run. Once a base system is up and running, we will begin
producing stable versions that have well documented effects.

# Contributing
We would love the help of other developers! Debugging is an especially helpful task.
If you encounter a bug during usage, please open an issue.


#DEV NOTES
Sync
   -Server Side
   -Client Side
Filter
   -Server
Meta
   -Server

STRETCH GOALS:
-IOS/MAC
-CLIENT PUSHING
-CLIENT META DATA
-Filtering
-Not Local/ Webservice
-Streaming

Potential Issues:
Bloat
Easy to spoof
Legality

Server:
-Manage Connections on Notifications
-Ability to use local/external storage
-Blacklist/whitelist
-Encryption/Oauth
-Generic REST API for meta data
-File Transfer / Streaming
   * Protocol TBD
-Non-local web managment interface

Streaming is short lived:
Simple connect, the transfers (can be done through REST?) (or websockets?)
