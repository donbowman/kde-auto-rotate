# kde-auto-rotate

This script allows a convertible tablet to work with KDE for
auto-rotation. It causes all pointers to also rotate orientation.

It disables itself if there is an external display attached.

The install script will setup the systemd and set the path

## Notes

This relies on `gawk` being installed, and `iio-sensor-proxy`.
You may need:

`apt-get install gawk iio-sensor-proxy`
