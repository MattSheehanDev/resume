### Build

Although it should build with any LaTeX engine, specifically I use the MacTex 2018 distribution with XeLaTeX.

The preview image is generated via ImageMagick
```sh
magick convert -density 300 matthew_sheehan_resume.pdf -quality 90 -alpha off resume_preview.png
```

### Preview
![Resume Screenshot](/resume_preview.png)

### License
Format is MIT but all the data is owned by Matt Sheehan.
