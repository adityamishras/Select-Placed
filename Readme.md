## Selecet And Place

This HTML, CSS and JS project based on selection of image and that selected image get replaced by main image.

## JavaScript

<h4>How it works:</h4>
<ul>
    <li><bold>Step 1:</bold> let mainimage and small_image from html using document.getelementbyId and document.getelementbyClassName</li>
    <li><bold>Step 2:</bold> Create a Function when user Click on small image then small inage replaced by main image</li>
    
   ```Javascript
    small_img[0].onclick = function () {
    mainimage.src = small_img[0].src
    }
```
 <li><bold>Step 3:</bold> Here small_image[0] represents, the image with zero index because we have many small image and we take all this images as an array</li>
 <li><bold>Step 4:</bold> Apply this same function for all up to last index small_image[i].</li>

 ```JavaScript
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
</ul>

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
## Screenshot
<img src="https://github.com/adityamishras/Select-Placed/assets/136791974/07ad46f8-8de7-457f-95fd-97774fb29414" width="400px"/>


## Output
<video src="https://github.com/adityamishras/Select-Placed/assets/136791974/d0d149fa-d383-4fd9-875a-91832765e04f
" controls autoplay></video>

## Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adityamishras/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adityamishras)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/adityamishras)

