Videophile Quality MPV configs, now auto slects correct colour gamut, tone mapping and transfer function to enable HDR signalling
without needing to change the windows HDR settings, correctly identifies and maps, SDR (bt709), HDR 10 and HLG.

Only settings requring modification are:

--target-peak=2300  (run a widows HDR calibration on your display, memorise the max numberof NITS in the full screen test and use 
this value in place of 2300 in mpv.conf)

--fs-screen=0 This is the fullscreen display, change the number to match your display device.

e displays stats for 5 seconds, E toggles stats, whilst displayed use 1,2 and 3 to switch between stat pages.

To pass Youtube and other browser based video platforms to MPV install the following browser extension for Chrome or Edge, once installed goto extension settings and make the button visable. https://chromewebstore.google.com/detail/play-with-mpv/hahklcmnfgffdlchjigehabfbiigleji

Ensure you have downloaded the latest version of YT.DLP https://github.com/yt-dlp/yt-dlp/ (yt-dlp_win.zip) extract the exe to the same directory as MPV. There is a working version of the exe in this repository.

Run the server MPV Browser Server.exe, now open a youtube video in your browser and click the MPV button, you should see the request passed to the server window, after a couple of seconds the MPV window should open.
