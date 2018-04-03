Graphite Cross Platform Install Notes
=====================================

Instructions for running Graphite on Windows is now obsolete since there are cross platform versions of carbon and whisper written in Go.

```https://github.com/go-graphite```

Old Windows-Graphite-Install-Notes
==================================

Installation notes collected while installing Graphite on Windows

###
This was a long time ago but as I recall:
* Change some printf arguments to be standards compliant
* Use Jython? 
* Remove Unix specific stuff, such as daemon and fork assumptions
* As I recall there were some stability issues with the web interface and so greenlets were used for http instead.
* Remove any modules that compile to a binary.  Use a cross platform version instead.
