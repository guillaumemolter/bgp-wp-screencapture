#Screen Capture
by [Guillaume Molter](http://guillaumemolter.me) for [B+G & Partners SA](http://bgcom.ch/)
##A screen capture plugin for Wordpress based on PhantomJS


###Disclaimer
This plugin requires full access and control over your webserver. If you don't fully understand terms like SSH, sudo and package installation this plugin is not for you.


###Installation

- This plugin comes with the Cent OS 64 bit version of PhantomJS. If your Webserver is using a different OS you will need to replace the binaries by the one for your OS. You can find them [here](http://phantomjs.org/download.html) and replace the binaries in **/bin/** (make sure to preserve the binaries filename).
- Give execution rights to **/bin/**  if it's not already the case.

####Requirements
The plugin has no dependencies however PhantomJS needs a few things to work properly:

- Some base libraries are necessary for rendering : FreeType, Fontconfig
- Please also make sure that the basic font files are available in the system.

More details [here](http://phantomjs.org/download.html).