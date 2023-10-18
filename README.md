# ffmpeg convert video formats from the command line

## brew install ffmpeg

<img width="499" alt="Screenshot 2023-08-18 at 6 11 04 AM" src="https://github.com/sudo-self/ffmpeg/assets/119916323/631ad4c4-c978-4c24-b509-d8bb93bb4249">

### .mov ---> .mp4

### ffmpeg -i iphone.mov -vcodec h264 iphone.mp4

### .mov ---> .gif

### ffmpeg -i iphone.mov iphonez.gif

### ffmpeg -i in.mov -pix_fmt rgb8 -r 10 output.gif && gifsicle -O3 output.gif -o output.gif### 

### .mov ---> .ogg

### ffmpeg -i iphone.mov iphone.ogg

# ffmpeg version 6.0 Copyright (c) 2000-2023 the FFmpeg developers
### built with Apple clang version 14.0.3 (clang-1403.0.22.14.1)
 
###  ffmpeg -i /Users/admin/Downloads/IMG_0761.MOV  -vcodec h264 iphonee.mp4
ffmpeg version 6.0 Copyright (c) 2000-2023 the FFmpeg developers
  built with Apple clang version 14.0.3 (clang-1403.0.22.14.1)
<img width="162" alt="Screenshot 2023-08-18 at 6 15 01 AM" src="https://github.com/sudo-self/ffmpeg/assets/119916323/9892f8ea-64a8-4de7-9d3e-377d05f197d7">
<img width="1440" alt="Screenshot 2023-08-18 at 8 47 25 AM" src="https://github.com/sudo-self/ffmpeg/assets/119916323/99e85dd0-d871-4bc6-be19-5d15e8f4e4ae">


