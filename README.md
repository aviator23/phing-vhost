phing-vhost
===========

Phing build project to set up an Apache2 virtual host, on a Debian-style linux distro.

Notes
-----

###ServerAlias vhost entries

In addition to a Servername, two ServerAlias entries are included for the vhost: 

 * SITENAME.localhost
 * SITENAME.hostname

This is just a convenience for developing on my machines at home. Since I often move Drupal websites between laptop, desktop, and home server, it lets me view the version on a specific machine if I need to.

If you don't need these, just remove the ServerAlias lines from apache2.vhost.template.
