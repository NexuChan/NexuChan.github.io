<style>
    h1,h2{text-align:center;}
    #horiline{width:750px;}
</style>
# Dhiraagu throttle speed exploit

### So basically, dhiraagu users can use peer 2 peer services between each other using the full speed of the package they have. It mostly useful for file sharing ( which i'll be discussing mostly about in here ) and remote desktop services.
### I don't know if this is how they have the servers configued or not but who cares right?. They have us blocked with shitty bandwidth limits anyway. So why not just exploit this.
### As far as i know Malé, hulhumalé and Villigilli residents that use dhiraagu can use this exploit between each other. 
<hr>
# Screen share  / Remote Desktop Services

For this you will need to use a remote desktop service which uses peer to peer connections to share desktops. I recommend using [Parsec](https://parsecgaming.com). If there is an issue with it go through their F.A.Q page. It should have answers to almost all the issues an individual can have.
<hr>
# File Sharing

**For this you will need to have a torrent client on both parties computer or an FTP server setup on a computer where everyone can use and an FTP client to connect to that server.** 

## FTP

For FTP, i recommend using [FileZilla](https://filezilla-project.org/) as their software is free to use, even provides an easy to setup server application for windows. 

FTP is a good way to share files especially if they are below 1-3 Gb in total (depends on your connection), as you can't pause using FTP softwares (in my experience).

If you want to know how to setup an FTP server hit me up in discord, i'll teach you how to do it or do it for you (all up to you). Or if you need detailed tutorial let me know so that i can create a few pages for this.

<p style="Color: #159957;">Session: 0505fb42050477fb985399d8541c5d9aec6e9011e88c2d0801a522a9c679ce2c48</p>
<p style="Color: #159957;">Wire: @nexuchan</p>
<p style="Color: #159957;">Email: nexuchan@protonmail.com</p>

## Torrent

<hr id="horiline">

If the folder or file you want is big, i would suggest using torrent to transfer the files.<br>You can create torrents using your torrent client (uTorrent or BitTorrent), like so.<br><br><img src="https://i.imgur.com/0YcjvVC.png"><br>
> For trackers you can use these as defaults. Just copy paste them.
> ```
>udp://tracker.openbitorrent.com:80/announce
>
>udp://tracker.opentrackr.org:1337/announce
>```
> Or you can use your own tracker using [qbittorent's embedded tracker feature](https://github.com/qbittorrent/qBittorrent/wiki/How-to-use-qBittorrent-as-a-tracker)

<br>

>If you get a memory crash error when trying to create a Torrent using the torrent client, use [this](https://kimbatt.github.io/torrent-creator/) to make the torrent file. Don't worry the script runs within your device using only your HDD. 
>
> Atfer it's done, download the torrent file. 
>
> Open your torrent client, click ***File*** in the main menu ribbon and then click ***Add torrent (Choose save dir)*** or ***press CTRL and D*** simultaneously (hehe i know just made you read through that for lolz c:). 
>
>Search for the torrent file first, select it and press enter. After that search for the folder where the files are in and then press enter. 
>
> Your torrent client will start checking for files, after its done checking all the files, the client will start seeding (if it doesn't, try again. If it doesn't work a second time gws buddy.). 