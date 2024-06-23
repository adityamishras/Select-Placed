## Selecet And Place

-- This HTML, CSS and JS project based on selection of image and that selected image get replaced by main image.

## JavaScript

```JavaScript

let mainimage = document.getElementById('mainimage');

let small_img = document.getElementsByClassName('small_img');

small_img[0].onclick = function () {
    mainimage.src = small_img[0].src
}
small_img[1].onclick = function () {
    mainimage.src = small_img[1].src;
}
small_img[2].onclick = function () {
    mainimage.src = small_img[2].src;
}
small_img[3].onclick = function () {
    mainimage.src = small_img[3].src;
}
small_img[4].onclick = function () {
    mainimage.src = small_img[4].src;
}

```
