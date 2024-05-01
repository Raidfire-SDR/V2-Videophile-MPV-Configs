Videophile Quality MPV configs


60/120hz@24fps working enabling max refresh rate of your device with the fps output matching the input.

Only settings requring modification are:


--fs-screen=0 This is the fullscreen display, change the number to match your display device.

e displays stats for 5 seconds, E toggles stats, whilst displayed use 1,2 and 3 to switch between stat pages.

Note mpv keyboard bindings are case sensitive and you can create your own by editing input.conf. 

To pass Youtube and other browser based video platforms to MPV install the following browser extension for Chrome or Edge, once installed goto extension settings and make the button visable. https://chromewebstore.google.com/detail/play-with-mpv/hahklcmnfgffdlchjigehabfbiigleji

Ensure you have downloaded the latest version of YT.DLP https://github.com/yt-dlp/yt-dlp/ (yt-dlp_win.zip) extract the exe to the same directory as MPV. There is a working version of the exe in this repository, if you configured updates during installation use the file above the next time it updates the latest version will be downloaded by the standard mpv updater, or run the update.bat file.

Run the server MPV Browser Server.exe, now open a youtube video in your browser and click the MPV button, you should see the request passed to the server window, after a couple of seconds the MPV window should open.

F displays the youtube quality menu.
mouse right pause/play
middle mouse - stats
mouse fwd button - osd auto
mouse back button - osd never
