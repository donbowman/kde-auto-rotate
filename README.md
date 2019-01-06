# kde-auto-rotate

This script allows a convertible tablet to work with KDE for
auto-rotation. It causes all pointers to also rotate orientation.

It disables itself if there is an external display attached.

The install script will setup the systemd and set the path

## Notes

This relies on `gawk` being installed, and `iio-sensor-proxy`.
You may need:

`apt-get install gawk iio-sensor-proxy`

## Backdrop

If you wish to have the backdrop change automatically on rotation,
you can create these 4 files in ~/.config/auto-rotate:

- normal.jpg
- bottom-up.jpg
- right-up.jpg
- left-up.jpg

Make each image be the exact backdrop you want, as a JPEG.
