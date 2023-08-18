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

 echo "# ffmpeg" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sudo-self/ffmpeg.git
git push -u origin main
Initialized empty Git repository in /Users/admin/Desktop/.git/
[main (root-commit) 317f4d0] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 217 bytes | 217.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sudo-self/ffmpeg.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
