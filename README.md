Motion Photos Script
====================

The Google Pixel 6a creates files like *.MP.jpg that contain
video in addition to an image.  This git repo contains a bash script that
extracts the video into a separate file.

# Run on single file

`./mvimg_jpg_extract.sh filename.MP.jpg`

# Run on entire directory

`./mvimg_jpg_extract.sh $(ls)`
