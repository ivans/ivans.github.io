# Upute za pretvaranje prezentacije iz pdf u ppt

## Pretvaranje stranica u svg
```
pdf2svg prezentacija\ -\ Ivan\ Senji\ -\ jMonkeyEngine.pdf slike/prezentacija-%02d.svg all
```

## Pretvaranje svg-ova u png
```
mogrify -format png -density 200 -- *.svg
```

## svg je moguće direktno importati u LibreOffice Impress pomoću https://extensions.libreoffice.org/extensions/photo-album
* photo album treba hackirati da se doda support za svg

## xlsx ne podržava svg pa treba napraviti import Photo Album iz png-ova i onda to sejvati kao xlsx

# Prezentacija je uploadana na Google Drive
https://drive.google.com/drive/folders/1jQsYs9WWtoOUCbqZETE0rkzw_kgDO8L_?usp=sharing

# Link za pokazivanje animacije
http://www.identalia.com/en/3d/?id-animacija=305651&jezik=en&ts=440a75345d61446f390c847f34a133e2&ver=3
https://goo.gl/9Tj6rE


#TODO
