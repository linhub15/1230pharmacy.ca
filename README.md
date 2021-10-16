# Dev
* `hugo serve`

## 3rd Party Dependencies
* Bootstrap v5.1.1
 


## Image Manipulation
* resize with named output `convert -resize 50% image.jpg out.jpg`
* resize with aspect ratio `mogrify -resize 50% *.jpg`
* resize to specific dimensions `mogrify -resize 500x200 *.png` 
* compress `jpegoptim *.jpg`