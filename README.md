# muse-eye-tracking
Analyzing Muse headband sensor data to track eye motion. Done for the Codestellation Nov. 14-15 hackathon.

### Requirements
* [pyliblo module](http://das.nasophon.de/pyliblo/)
  * `sudo apt-get install liblo`
  * `sudo pip install pyliblo`
* [Muse SDK](https://sites.google.com/a/interaxon.ca/muse-developer-site/download)
  * download the [installer](http://storage.googleapis.com/ix_downloads/musesdk-3.4.1/musesdk-3.4.1-linux-installer.run)
  * `cd ~/Downloads/`
  * `chmod +x musesdk-3.4.1-linux-installer.run`
  * `./musesdk-3.4.1-linux-installer.run`

### Usage
* `git clone https://github.com/joeylmaalouf/muse-eye-tracking.git`
* `cd muse-eye-tracking`
* `python muse_thresholding.py`
