### Build

Although it should build with any LaTeX engine, specifically I use the MacTex 2018 distribution with pdfTeX or Latexmk.

The preview image is generated via ImageMagick
```sh
magick convert -density 300 matthew_sheehan_resume.pdf -quality 90 -alpha off resume_preview.png
```

I edit in VSCode using the [Text Workshop](https://github.com/James-Yu/LaTeX-Workshop) extension. There are a few shortcuts that I don't use enough to always remember.
```sh
# Build
Cmd + Alt + b
# Clean
Cmd + Alt + c
```

### Preview
![Resume Screenshot](/resume_preview.png)

### License
Format is MIT but all the data is owned by Matt Sheehan.
