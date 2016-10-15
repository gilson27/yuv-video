# yuv-video

[![GitHub license](https://img.shields.io/badge/license-New%20BSD-blue.svg)](https://raw.githubusercontent.com/gilson27/yuv-video/master/LICENSE)

A nodejs module to read YUV video file and convert it to different formats.

Raw videos (Videos captured by camera before processing) are mainly in two formats: RGB and YUV. This module aims to help users to read YUV
 videos and process it the way they want in their code. Processing applications include converting it to another format, streaming the video over ffmpeg,
 video quality analysis etc.

Currently this module supports the following formats:
* YV12 - 8bit planar 420
* V210 - 10bit interlaced 422

### User Guide
 Install module using npm
 
 ```
 npm install yuv-video
 ```
 
 JSdoc can be found here: https://github.com/gilson27/yuv-video/jsdoc
