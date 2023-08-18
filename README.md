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

# ffmpeg version 6.0 Copyright (c) 2000-2023 the FFmpeg developers
### built with Apple clang version 14.0.3 (clang-1403.0.22.14.1)
 
###  ffmpeg -i /Users/admin/Downloads/IMG_0761.MOV  -vcodec h264 iphonee.mp4
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
Input #0, mov,mp4,m4a,3gp,3g2,mj2, from '/Users/admin/Downloads/IMG_0761.MOV':
  Metadata:
    major_brand     : qt  
    minor_version   : 0
    compatible_brands: qt  
    creation_time   : 2023-03-05T23:19:22.000000Z
    com.apple.quicktime.location.accuracy.horizontal: 41.000000
    com.apple.quicktime.location.ISO6709: +38.8568-104.7892+1874.456/
    com.apple.quicktime.make: Apple
    com.apple.quicktime.model: iPhone 12 Pro Max
    com.apple.quicktime.software: 16.2
    com.apple.quicktime.creationdate: 2023-03-05T16:19:22-0700
  Duration: 00:00:09.41, start: 0.000000, bitrate: 11367 kb/s
  Stream #0:0[0x1](und): Video: hevc (Main 10) (hvc1 / 0x31637668), yuv420p10le(tv, bt2020nc/bt2020/arib-std-b67), 1920x1080, 11171 kb/s, 29.98 fps, 29.97 tbr, 600 tbn (default)
    Metadata:
      creation_time   : 2023-03-05T23:19:22.000000Z
      handler_name    : Core Media Video
      vendor_id       : [0][0][0][0]
      encoder         : HEVC
    Side data:
      DOVI configuration record: version: 1.0, profile: 8, level: 4, rpu flag: 1, el flag: 0, bl flag: 1, compatibility id: 4
      displaymatrix: rotation of -90.00 degrees
  Stream #0:1[0x2](und): Audio: aac (LC) (mp4a / 0x6134706D), 44100 Hz, stereo, fltp, 148 kb/s (default)
    Metadata:
      creation_time   : 2023-03-05T23:19:22.000000Z
      handler_name    : Core Media Audio
      vendor_id       : [0][0][0][0]
  Stream #0:2[0x3](und): Data: none (mebx / 0x7862656D), 0 kb/s (default)
    Metadata:
      creation_time   : 2023-03-05T23:19:22.000000Z
      handler_name    : Core Media Metadata
  Stream #0:3[0x4](und): Data: none (mebx / 0x7862656D), 0 kb/s (default)
    Metadata:
      creation_time   : 2023-03-05T23:19:22.000000Z
      handler_name    : Core Media Metadata
  Stream #0:4[0x5](und): Data: none (mebx / 0x7862656D), 34 kb/s (default)
    Metadata:
      creation_time   : 2023-03-05T23:19:22.000000Z
      handler_name    : Core Media Metadata
Stream mapping:
  Stream #0:0 -> #0:0 (hevc (native) -> h264 (libx264))
  Stream #0:1 -> #0:1 (aac (native) -> aac (native))
Press [q] to stop, [?] for help
[libx264 @ 0x13de12980] using cpu capabilities: ARMv8 NEON
[libx264 @ 0x13de12980] profile High 10, level 4.0, 4:2:0, 10-bit
[libx264 @ 0x13de12980] 264 - core 164 r3095 baee400 - H.264/MPEG-4 AVC codec - Copyleft 2003-2022 - http://www.videolan.org/x264.html - options: cabac=1 ref=3 deblock=1:0:0 analyse=0x3:0x113 me=hex subme=7 psy=1 psy_rd=1.00:0.00 mixed_ref=1 me_range=16 chroma_me=1 trellis=1 8x8dct=1 cqm=0 deadzone=21,11 fast_pskip=1 chroma_qp_offset=-2 threads=12 lookahead_threads=2 sliced_threads=0 nr=0 decimate=1 interlaced=0 bluray_compat=0 constrained_intra=0 bframes=3 b_pyramid=2 b_adapt=1 b_bias=0 direct=1 weightb=1 open_gop=0 weightp=2 keyint=250 keyint_min=25 scenecut=40 intra_refresh=0 rc_lookahead=40 rc=crf mbtree=1 crf=23.0 qcomp=0.60 qpmin=0 qpmax=81 qpstep=4 ip_ratio=1.40 aq=1:1.00
Output #0, mp4, to 'iphonee.mp4':
  Metadata:
    major_brand     : qt  
    minor_version   : 0
    compatible_brands: qt  
    com.apple.quicktime.creationdate: 2023-03-05T16:19:22-0700
    com.apple.quicktime.location.accuracy.horizontal: 41.000000
    com.apple.quicktime.location.ISO6709: +38.8568-104.7892+1874.456/
    com.apple.quicktime.make: Apple
    com.apple.quicktime.model: iPhone 12 Pro Max
    com.apple.quicktime.software: 16.2
    encoder         : Lavf60.3.100
  Stream #0:0(und): Video: h264 (avc1 / 0x31637661), yuv420p10le(tv, bt2020nc/bt2020/arib-std-b67, progressive), 1080x1920, q=2-31, 29.97 fps, 30k tbn (default)
    Metadata:
      creation_time   : 2023-03-05T23:19:22.000000Z
      handler_name    : Core Media Video
      vendor_id       : [0][0][0][0]
      encoder         : Lavc60.3.100 libx264
    Side data:
      cpb: bitrate max/min/avg: 0/0/0 buffer size: 0 vbv_delay: N/A
      DOVI configuration record: version: 1.0, profile: 8, level: 4, rpu flag: 1, el flag: 0, bl flag: 1, compatibility id: 4
      displaymatrix: rotation of -0.00 degrees
  Stream #0:1(und): Audio: aac (LC) (mp4a / 0x6134706D), 44100 Hz, stereo, fltp, 128 kb/s (default)
    Metadata:
      creation_time   : 2023-03-05T23:19:22.000000Z
      handler_name    : Core Media Audio
      vendor_id       : [0][0][0][0]
      encoder         : Lavc60.3.100 aac
frame=  174 fps=9.5 q=41.0 size=    4864kB time=00:00:08.84 bitrate=4504.0kbits/s speed=0.482x    
