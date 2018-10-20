# Pico-RssMaker
Very basic RSS plugin for Pico. Generates RSS feed of all pages with a date. . The plugin is based on:

* [Pico-RSS-Plugin](https://github.com/gilbitron/Pico-RSS-Plugin)
* [Pico_Sitemap](https://github.com/DaveKin/Pico_Sitemap)
* [Pico_Dummy Plugin](https://github.com/picocms/Pico/blob/master/plugins/DummyPlugin.php)

## About
I put this together by combining the techniques of the two above plugins as I could not get Pico-RSS-Plugin to work because it's for an older version of the CMS. I essentially coverted the twig template that Pico-Rss used into PHP, and used Pico-Sitemap as a guide for how to do this in the newer framework.

## Disclaimer
I'm not great at PHP (part of the reason I use Pico in the first place). If you see something that can be improved, I'll be very grateful. I only made this for a website I manage, but thought it best to give back to the community.

# Installation
1. Copy to RssMaker.php to the plugins folder.
2. Add the following line to your config.php:

    $config['RssMaker.enabled'] = true;
    
3. Your feed URL will be example.com/feed. Navigate here to make sure it works.

# Compatibility
I've not extensively tested the plugin, but it's worked fine on the following installations (testament to the hard work the Pico team put into backwards compatibility in Pico 2).
* 1.0.4
* 2.0.2
