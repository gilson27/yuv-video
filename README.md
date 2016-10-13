# yuv-video

A nodejs module to read YUV video file and convert it to different formats.

Raw videos (Videos captured by camera before processing) are mainly in two formats: RGB and YUV. This module aims to help users to read YUV
 videos and process it the way they want in their code. Processing applications include converting it to another format, streaming the video over ffmpeg,
 video quality analysis etc.

Currently this module supports the following formats:
* YV12 - 8bit planar 420
* V210 - 10bit interlaced 

### User Guide
 Install module using npm
 
 ** npm install yuv-video **
 
 JSdoc can be found here: https://github.com/gilson27/yuv-video/jsdoc
