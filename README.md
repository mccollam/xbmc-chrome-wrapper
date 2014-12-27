xbmc-chrome-wrapper
===================

A simple wrapper for XBMC to allow proper handling of different streaming media in different browsers

Purpose
=======

Amazon streaming video does not work in Chrome on Linux.  Netflix does not work in Firefox in Linux.  The Right Way™ to fix this would be to have the XBMC/Kodi plugins call the correct browser, but this way was faster and gets the job done.

This script will look at the URL of the video being played and direct it to the proper browser.


Installation
============

Prerequisite: installation of both Google Chrome and Firefox with Pipelight installed and configured.

Installation: Rename the existing Chrome binary to "google-chrome-real":

     sudo mv /usr/bin/google-chrome /usr/bin/google-chrome-real

Then put the script in its place:

     sudo cp google-chrome /usr/bin/


