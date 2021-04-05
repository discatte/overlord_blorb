# overlord blorb
praise to the blorb

# rendering
Run povray with `povray blorb.pov +H1080 +W1920 +A +AM2 +Q11` or for an animation use `povray blorb.pov anim.ini`

To make a movie (requires FFmpeg) `ffmpeg -loop 1 -framerate 60 -i blorb%03
d.png -t 10 -pix_fmt yuv420p blorb.mp4`

To make a gif (requires Image Magick) `convert -delay 2 -dispose Background blorb*.png discque-hearto-pulse.gif`

![discque](https://raw.githubusercontent.com/discatte/blorb/main/blorb.png)
