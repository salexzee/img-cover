IMG COVER
======

Img Cover is a tiny bit of CSS code that makes it easy to set up images with hover covering hover text.

To use Img Cover right out of the box, first include it in your HTML above your own CSS file:

```HTML
<link rel="stylesheet" href="./img-cover.css">
<link rel="stylesheet" href="./your-styles.css">
```

Then just set up the images you would like to use it on.

```HTML
<div class="img-cover">
  <img src="http://your-image.jpg" alt="Your image alt." />
  <div class="cover">
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    </p>
  </div>
</div>
```
Img Cover has default sizes of 200px for the height and width of images. If you want to change from the defaults, change it on the `.img-cover` class in your CSS file.

```CSS
.img-cover {
  width: 650px;
  height: 650px;
}
```

There is currently nothing special to handle round images, but that will be added soon.
