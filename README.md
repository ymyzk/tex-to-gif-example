# tex-to-gif-example
Example of [tex-to-gif](https://github.com/ymyzk/tex-to-gif).

## How to use
```bash
git clone https://github.com/ymyzk/tex-to-gif-example.git
./tex-to-gif/tex-to-gif.sh \
  --tex-build 'latexmk document.tex' \
  --tex-pdf 'document.pdf' \
  --image-geometry '300x' \
  --image-tile '2x' \
  --animation-delay 20
```

## Result
![animation](animation.gif)
