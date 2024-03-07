# Preview GIFs

The preview GIFs are recorded with OBS Studio at 1920x1080, cut to a length of exactly two seconds and converted to a GIF with the following command:

```bash
gifski --fps 30 -W 320 -H 180 -o effect.gif effect.mp4
```