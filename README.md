script.xbmc.hue.ambilight
=========================

![ScreenShot](http://meethue.files.wordpress.com/2013/01/plugin2.png?w=400)

An XBMC add-on that controls Philips Hue lights. It supports two modes of operation:

 - Theatre mode

Dims the the Philips Hue lights as soon as a movie starts playing, and turns the lights back on once the movie is done

- Ambilight mode

Turns your Philips Hue lights in a room-sized ambilight

Donations
---------
If you enjoy the add-on, donations are always welcome :)

[![PayPal]( https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=48ZKAZK6QHNGJ&lc=NL&item_name=script%2exbmc%2ehue&currency_code=EUR)

Installation
------------

The add-on depends on the XBMC add-on "requests" for the ambilight mode.

**XBMC add-on script.module.requests**

 - Download the add-on as a ZIP file from https://github.com/beenje/script.module.requests
  - (Right click on the "ZIP" icon and select "Download Linked File").
 - Open XBMC
 - Go to `System -> Settings -> Add-ons -> Install from zip file`
 - Select the zip file.

**XBMC add-on script.xbmc.hue.ambilight**

 - Download the add-on as a ZIP file from the top of this page
   - (Right click on the "ZIP" icon and select "Download Linked File")
 - Open XBMC
 - Go to `System -> Settings -> Add-ons -> Install from zip file`
 -  Restart XBMC and configure the add-on:
   - `System -> Settings -> Add-ons -> Enabled add-ons -> Services -> XBMC Philips Hue`
   - Run `Start auto discovery of bridge IP and User`.

Note for Raspberry Pi users:

 - Save the add-on configuration by exiting XBMC before shutting down the Pi completely
 - Ambilight mode doesn't work on a Raspberry Pi due to the way it renders video

Release history
---------------
  * 2013-05-25 v 0.5.0 Debug logging, livingwhite lights
  * 2013-05-04 v 0.4.0 Advanced settings
  * 2013-04-25 v 0.3.6 Custom dimmed brightness in theatre mode
  * 2013-04-02 v 0.3.4 Ambilight is more responsive
  * 2013-04-01 v 0.3.3 Rename to script.xbmc.hue.ambilight
  * 2013-02-25 v 0.3.1 Improved handling for grouped lights
  * 2013-01-27 v 0.1.0 Initial release

Contributing
------------

Want to contribute? Great! I don't plan on actvily extending this code, but will accept push requests and help with bug reports. You can contact me on my Github profile page.

Feel free to fork away and have fun!
