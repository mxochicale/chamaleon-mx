


```
convert -density 600 presentation.ml4mx.pdf -strip -resize @1048576 PNG8:slide-%02d.png
convert -layers OptimizePlus -delay 75 slide-0?.png slide-1[01234].png -delay 300 slide-1[567].png -loop 0 slides.gif
```


http://phyletica.org/imagemagick/
