RT
====
Copyright 2018-2020 Radio Town <radio@radiotown.fi>
Project Page: [RT](https://github.com/okramalem/RT)

ABOUT
=====
This small application sits in the system tray and updates a text
file with the currently playing audio track.

It supports the following media players:
* [Spotify](https://www.spotify.com/)
* [iTunes](https://www.apple.com/itunes/)

If you choose to use iTunes, RT will automatically launch it. (This
is the behavior of the COM API and there's nothing I can do about it.) If you
only use Spotify, you don't have to worry about it.

To switch between players just right-click on the icon in the system tray.

RT will write a generic format output to a file called `RT.txt` within the
same folder as `RT.exe`.  If you choose to save information to separate files, 
the files will be called `RT_Artist.txt`, `RT_Track.txt`, `RT_Album.txt`, 
and `RT_History.txt` (track history).

VARIABLES
=========
There are a handful of variables you can use within the Output Settings.

These variables only affect the output of RT.txt itself.

* $$t = Track Title
* $$ut = TRACK TITLE
* $$lt = track title
* $$a = Track Artist
* $$ua = TRACK ARTIST
* $$la = track artist
* $$l = Track Album
* $$ul = TRACK ALBUM
* $$ll = track album
* $$i = Spotify track ID
* $$n = New line

HOTKEYS
=======
* **Next Track:** Ctrl, Alt, ]
* **Previous Track:** Ctrl, Alt, [
* **Volume Up:** Ctrl, Alt, + (iTunes Only)
* **Volume Down:** Ctrl, Alt, - (iTunes Only)
* **Mute Track:** Ctrl, Alt, M (iTunes Only)
* **Pause Track:** Ctrl, Alt, P
* **Play/Pause Track:** Ctrl, Alt, Enter (Pause iTunes Only)
* **Stop Track:** Ctrl, Alt, Backspace (iTunes Only)

DONATIONS
=========
RT is free; however, I've received a lot of requests from people wishing
to donate. If you'd like to donate it's entirely up to you. You may donate
here: [PayPal](https://paypal.me/radiotown)
