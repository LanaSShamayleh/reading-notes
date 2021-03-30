# Readings : Images, Color, Text

>During the creation and design the webpage ,you might want to include a logo, photograph, illustration, diagram, or chart and from **DUCKETT HTML BOOK**, I learned that how to add images to pages and choose right format depending on the design of the pages. First of all, if the designer start to build his website from the scratch ,there's a need to organize the images that will be used in the website in the folders and subfolders , because this process help the designer to imagine how the structure of a website is organized .
>
>The photographs are saved as **JPEGs** in order to insert them in the website to have the best appearance; and the illustrations or logosare saved as **GIFs** .So , which image format to use and when?
>>
- **JPEG** : This format can be used for all images that have a variation in colour and intensity is smooth.
>>
- **PNG** :This format can be used for images with text & objects with sharp contrast edges like logos.
>>
- **GIF** : This format van be used for images that contain animations

>Where an image is placed in the code will affect how it is displayed.photographs are saved as **JPEGs**; illustrations or logosare saved as **GIFs** . There are three examples of image placement and how it's results will be, such as :
>>
- **Before a paragraph** : The paragraph starts on a new line after the image.
>>
- **Inside the start of a paragraph** : The first row of text aligns with the bottom of the image.
>>
- **In the middle of a paragraph**: The image is placed between the words of the paragraph that it appears in.

> How to add the image by using HTML :
>>`<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" />`
>>
>> Where :
>>
>>**src** : This tells the browser where it can find the image file.
>>
>>**alt** :This provides a description of the image if it doesn't appear .
>>
>>**title**: This provides additional information bout img as a tootip when the user hovers over the image.
>>
>>**height**:This specifies the height of the image in pixels.
>>
>>**width**:This specifies the width of the image in pixels.

>There are three rules that should be applied when you are creating images for your website , like :
>>
- **Save images in the right format** :The Websites mainly use images in ***jpeg, gif, or png format***.
>>
- **Save images at the right size**   :Choose the size of images and save them as the size that you would to appear on the website .
>>
- **Use the correct resolution**: the resolution of image refers to the number of dots per inch, and most computer screens only show web pages at 72 pixels per inch,so that when you save images with high resolution, the results in images will be larger than necessary and take longe time to download.

>HTML5 has introduced a new `<figure>` element for images that come with captions . As the following code :
>
>>
>>`<figure>`
>>`<img src="images/otters.jpg" alt="Photograph of two sea otters floating in water">`
>>`<br />`
>>`<figcaption>The Caption.</figcaption>`
>>`</figure>`
>>
>
>The ***Coloring*** is another thing must be used during the website building ,so that it helps convey the mood and brings your site to life. There are three ways to choose the colors in CSS: ***RGB values, hex codes, and color names***, and the color pickers can help you find the color you want, but make sure that there is enough contrast between a text and the background color in order to make people be able to read your content.
Also , ***The Formatting*** of your text have the significant effects on how readable your pages are.This formatting includes the controlling the space between lines of text, individual letters, and words. a text by using CSS can be aligned to the left, right, center, or justified.
