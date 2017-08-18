# Chiping out the image to chips

```
for f in `ls *.png` ; do convert $f -crop 256x256 ${f%.png}-chip%02d.png ; done
```
