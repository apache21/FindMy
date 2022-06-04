# FindMy
Query Apple's Find My network, based on all the hard work of https://github.com/seemoo-lab/openhaystack/ and @vtky and others.

## Install and Run
To install just clone this repo, to run a Mac (real or virtual) and an Apple ID are required

1. (Optional, if you don't have a MAC and/or Apple ID): Generate an Apple ID, and install the Catalina Pre-installed docker image from https://github.com/sickcodes/Docker-OSX#run-catalina-pre-installed-, and login to iCloud using your AppleID.
2. Add your public keys to `request_reports.py` at the top, and run (only internal tools are used, no dependencies).

This is using the ancient urllib on python 2.7 that comes with Catalina, so it might need some tweaking if you are on a more recent version.
But if you are using the docker from step 1 you should be good to go.

