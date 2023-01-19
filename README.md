# (not so) pmrp
(not so) pmrp (Poor Man's Radio Player) is a fork of pmrp (Poor Man's Radio Player - an Internet radio player script written in bash). Original pmrp can be found here:

[original-pmrp]

### What's changed :

  - Added capability to play streams that are not encoded in MPEG 1.0/2.0/2.5.
  - Extended section of Metal music radio streams, so now you can choose stations playing: heavy metal, thrash metal, death metal, black metal, speed/power metal, doom metal, nu metal, grindcore, grunge, metalcore, as well as stations playing mix of metal subgenres (Miscellaneous section).
  - Added some Hardcore Punk stations ("Hardcore" section in main menu).
  - Removed exit message. 

 
### Dependencies :

  - [mpg123] - for playing streams encoded in MPEG 1.0/2.0/2.5.
  - [mplayer] - for playing streams not encoded in MPEG 1.0/2.0/2.5 (and streams encoded in MPEG 1.0/2.0/2.5, but streamed using HTTPS). It can also play MPEG 1.0/2.0/2.5 encoded streams, but it's more resource intensive than mpg123. It's not strictly required, but stations with "(mplayer)" in name won't work without it.
  
  
### Installation :

Clone the repo
```sh
$ git clone https://github.com/lavix5/pmrp.git && cd pmrp
```
Copy it to /usr/local/bin/
```sh
$ sudo cp pmrp /usr/local/bin/
```
Make it executable
```sh
$ sudo chmod 755 /usr/local/bin/pmrp
```


### Usage :

Run in terminal
```sh
$ pmrp
```

[mplayer]:https://mplayerhq.hu/
[original-pmrp]:https://github.com/hakerdefo/pmrp
[mpg123]:http://mpg123.de/
