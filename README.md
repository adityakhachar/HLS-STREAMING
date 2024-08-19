# HLS Streaming Transcoding

This project demonstrates how to transcode a video into HLS (HTTP Live Streaming) format using FFmpeg within a Docker container and how to play it back using Video.js.

## Overview

This project converts a video file into an HLS stream, which is a popular format for streaming video over the web. The conversion is done using FFmpeg inside a Docker container. The HLS stream is then played back in a web page using Video.js, a widely used video player library.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [FFmpeg](https://ffmpeg.org/download.html) (if you are running commands locally outside of Docker)
- [Video.js](https://videojs.com/) (for the video player integration)

## Setup and Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/adityakhachar/HLS-STREAMING.git
  
