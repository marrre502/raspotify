# /etc/default/raspotify -- Arguments/configuration for librespot

# Device name on Spotify Connect
#DEVICE_NAME="raspotify"

# Bitrate, one of 96 (low quality), 160 (default quality), or 320 (high quality)
#BITRATE="160"

# Additional command line arguments for librespot can be set below.
# See `librespot -h` for more info. Make sure whatever arguments you specify
# aren't already covered by other variables in this file. (See the daemon's
# config at `/lib/systemd/system/raspotify.service` for more technical details.)
#
# To make your device visible on Spotify Connect across the Internet add your
# username and password which can be set via "Set device password", on your
# account settings, use `--username` and `--password`.
#
# To choose a different output device (ie a USB audio dongle or HDMI audio out),
# use `--device` with something like `--device hw:0,1`. Your mileage may vary.
#
#OPTIONS="--username pass --password pass --device /home/pi/music/spotify

# Uncomment to use a cache for downloaded audio files. Cache is disabled by
# default. It's best to leave this as-is if you want to use it, since
# permissions are properly set on the directory `/home/pi/raspotify'.
#CACHE_ARGS="--cache /home/pi/raspotify"

# By default, the volume normalization is enabled, add alternative volume
# arguments here if you'd like, but these should be fine.
#VOLUME_ARGS="--enable-volume-normalisation --linear-volume --initial-volume=0"

# Backend could be set to pipe here, but it's for very advanced use cases of
# librespot, so you shouldn't need to change this under normal circumstances.
#BACKEND_ARGS="--backend alsa"
