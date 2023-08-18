# ffmpeg convert video formats from the command line

## brew install ffmpeg

<img width="499" alt="Screenshot 2023-08-18 at 6 11 04 AM" src="https://github.com/sudo-self/ffmpeg/assets/119916323/631ad4c4-c978-4c24-b509-d8bb93bb4249">

### .mov ---> .mp4

### ffmpeg -i iphone.mov -vcodec h264 iphone.mp4

### .mov ---> .gif

### ffmpeg -i iphone.mov iphonez.gif

### .mov ---> .ogg

### ffmpeg -i iphone.mov iphone.ogg

<img width="162" alt="Screenshot 2023-08-18 at 6 15 01 AM" src="https://github.com/sudo-self/ffmpeg/assets/119916323/9892f8ea-64a8-4de7-9d3e-377d05f197d7">


 ffmpeg -i iphone.mov iphonez.gif
ffmpeg version 6.0 Copyright (c) 2000-2023 the FFmpeg developers
  built with Apple clang version 14.0.3 (clang-1403.0.22.14.1)
  configuration: --prefix=/opt/homebrew/Cellar/ffmpeg/6.0 --enable-shared --enable-pthreads --enable-version3 --cc=clang --host-cflags= --host-ldflags= --enable-ffplay --enable-gnutls --enable-gpl --enable-libaom --enable-libaribb24 --enable-libbluray --enable-libdav1d --enable-libmp3lame --enable-libopus --enable-librav1e --enable-librist --enable-librubberband --enable-libsnappy --enable-libsrt --enable-libsvtav1 --enable-libtesseract --enable-libtheora --enable-libvidstab --enable-libvmaf --enable-libvorbis --enable-libvpx --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxml2 --enable-libxvid --enable-lzma --enable-libfontconfig --enable-libfreetype --enable-frei0r --enable-libass --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenjpeg --enable-libspeex --enable-libsoxr --enable-libzmq --enable-libzimg --disable-libjack --disable-indev=jack --enable-videotoolbox --enable-neon
  libavutil      58.  2.100 / 58.  2.100
  libavcodec     60.  3.100 / 60.  3.100
  libavformat    60.  3.100 / 60.  3.100
  libavdevice    60.  1.100 / 60.  1.100
  libavfilter     9.  3.100 /  9.  3.100
  libswscale      7.  1.100 /  7.  1.100
  libswresample   4. 10.100 /  4. 10.100
  libpostproc    57.  1.100 / 57.  1.100
Input #0, mov,mp4,m4a,3gp,3g2,mj2, from 'iphone.mov':
  Metadata:
    major_brand     : qt  
    minor_version   : 0
    compatible_brands: qt  
    creation_time   : 2023-08-18T10:55:15.000000Z
    com.apple.quicktime.location.accuracy.horizontal: 35.000000
    com.apple.quicktime.location.ISO6709: +38.8567-104.7894+1874.518/
    com.apple.quicktime.make: Apple
    com.apple.quicktime.model: iPhone 12 Pro Max
    com.apple.quicktime.software: 16.2
    com.apple.quicktime.creationdate: 2023-03-12T23:38:48-0600
  Duration: 00:00:09.64, start: 0.000000, bitrate: 9604 kb/s
  Stream #0:0[0x1](und): Audio: aac (LC) (mp4a / 0x6134706D), 44100 Hz, stereo, fltp, 150 kb/s (default)
    Metadata:
      creation_time   : 2023-08-18T10:55:15.000000Z
      handler_name    : Core Media Audio
      vendor_id       : [0][0][0][0]
  Stream #0:1[0x2](und): Video: h264 (High) (avc1 / 0x31637661), yuv420p(tv, bt709, progressive), 812x1646, 9444 kb/s, 29.97 fps, 29.97 tbr, 600 tbn (default)
    Metadata:
      creation_time   : 2023-08-18T10:55:15.000000Z
      handler_name    : Core Media Video
      vendor_id       : [0][0][0][0]
      encoder         : H.264
  Stream #0:2[0x3](und): Data: none (mebx / 0x7862656D), 0 kb/s (default)
    Metadata:
      creation_time   : 2023-08-18T10:55:16.000000Z
      handler_name    : Core Media Metadata
  Stream #0:3[0x4](und): Data: none (mebx / 0x7862656D), 0 kb/s (default)
    Metadata:
      creation_time   : 2023-08-18T10:55:16.000000Z
      handler_name    : Core Media Metadata
Stream mapping:
  Stream #0:1 -> #0:0 (h264 (native) -> gif (native))
Press [q] to stop, [?] for help
[swscaler @ 0x138c18000] [swscaler @ 0x138c28000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x138c18000] [swscaler @ 0x1284c0000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x138c18000] [swscaler @ 0x1284d0000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x138c18000] [swscaler @ 0x1284e0000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x138c18000] [swscaler @ 0x1284f0000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x138c18000] [swscaler @ 0x128500000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x138c18000] [swscaler @ 0x128510000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x138c18000] [swscaler @ 0x128520000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x138c18000] [swscaler @ 0x128530000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c18000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c28000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c38000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c48000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c58000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c68000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c78000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c88000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x138c98000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118d68000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118d78000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118d88000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118d98000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118da8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118db8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118dc8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118dd8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118de8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118d68000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118d78000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118d88000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118d98000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118da8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118db8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118dc8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118dd8000] No accelerated colorspace conversion found from yuv420p to bgr8.
[swscaler @ 0x118d58000] [swscaler @ 0x118de8000] No accelerated colorspace conversion found from yuv420p to bgr8.
Output #0, gif, to 'iphonez.gif':
  Metadata:
    major_brand     : qt  
    minor_version   : 0
    compatible_brands: qt  
    com.apple.quicktime.creationdate: 2023-03-12T23:38:48-0600
    com.apple.quicktime.location.accuracy.horizontal: 35.000000
    com.apple.quicktime.location.ISO6709: +38.8567-104.7894+1874.518/
    com.apple.quicktime.make: Apple
    com.apple.quicktime.model: iPhone 12 Pro Max
    com.apple.quicktime.software: 16.2
    encoder         : Lavf60.3.100
  Stream #0:0(und): Video: gif, bgr8(pc, gbr/bt709/bt709, progressive), 812x1646, q=2-31, 200 kb/s, 29.97 fps, 100 tbn (default)
    Metadata:
      creation_time   : 2023-08-18T10:55:15.000000Z
      handler_name    : Core Media Video
      vendor_id       : [0][0][0][0]
      encoder         : Lavc60.3.100 gif
frame=  289 fps= 55 q=-0.0 Lsize=   77418kB time=00:00:09.61 bitrate=65994.3kbits/s speed=1.83x    
video:77418kB audio:0kB subtitle:0kB other streams:0kB global headers:0kB muxing overhead: 0.000025%
