# Read: 11 - Audio, Video, Images

From **DUCKETT HTML BOOK**, I learned how to Control size of images and align them in CSS and
add background images .

- Controlling size of images in CSS:

Specifying the image sizes makes pages to load more smoothly because the codes will often load before the images, and these codes telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download and we can control the size of an image using the width and height properties in CSS. the following codes of HTML and CSS show the controlling siza of an image :

>HTML CODE :

```HTML
<img src="images/image-large.jpg"
 class="large" alt='image' />
```

>CSS CODE :

```CSS
img.large {
width: 500px;
height: 500px;}
```

- Aligning images in CSS:

Web page authors are increasingly using the float property to align images. There are two ways to align :
1: The float property is added to the class that was created to represent the size of the image.
2: New classes are created with names such as align-left or align-right to align the images to the left or right of the page.
The images can be aligned both horizontally and vertically , and the following codes used to align the img to right :

>HTML CODE :

```HTML
<img src="images/image-large.jpg"
 class="large" alt='image' />
```

>CSS CODE :

```CSS
img.large {
width: 500px;
height: 500px;
float: right;
margin-left: 10px;}
```

- Adding background images:

This property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box.The followng CSS code use to add background to the body of a page .

>CSS CODE :

```CSS
body {
background-image: url("images/back-img.gif");}
```

## Practical Information

Also,I learned the concept of **Search Engine Optimization** that is the practice of trying to help our site appear on the top of search engine results when people look for specific keywords that may included in our website covers . In each page of our website there are seven key places where keywords (these keywords help people on the searching to find your site) can appear in order to improve its findability, such as :
Page Title , URL / Web Address , Headings , Text , Link Text , Image Alt Text and Page Descriptions .
Also,There are tools that suggest additional keywords to use such as:

- Google Ads.

- Wordtracker.

- Keyword Discovery.

Analytics tools such as **Google Analytics** allow us to see how many people visit our site, how they find it,and what they do when they get there.

To put our site on the web , we need a domain name and a web hosting server. The following key things that help the choosing which hosting company to use; disk space, bandwidth, and backups. The code of our site is transferred to the hosting company via File Transfer Protocol (FTP). There are a variety of FTP applications available such as FileZilla, CuteFTP, and SmartFTP.

## Flash

Flash allows us to add animations, video and audio to the web. When you export the movie
into SWF format, Flash creates code that you can use to embed the Flash movie in your page.
And, this code used the HTML `<object>` and `<embed>` tags.

## HTML Video and Audio

To add a video or an audio in our web page, the `<video>` and `<audio>` tags are used. Also , The `controls` attribute enables the native playback controls, and the using of the previous features show in the following code :

> ```HTML
><video controls>
><source src="vid1.mp4" type="video/mp4">
><source src="vid2.webm" type="video/webm">
></video>
>```
