# Audio, Video, Images

### ***Images*** 
The HTML ```<img> ``` tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The ```<img>``` tag creates a holding space for the referenced image.

The ```<img>```  tag is empty, it contains attributes only, and does not have a closing tag.

The ```<img>``` tag has two required attributes:

1. ```src``` - Specifies the path to the image
2. ```alt``` - Specifies an alternate text for the image

***Syntax***
```
<img src="url" alt="alternatetext">
```

- You can specify the dimensions of images using CSS. This is very helpful when you use the same sized images on several pages of your site.
- Images can be aligned both horizontally and vertically using CSS.
- You can use a background image behind the box created by any element on a page.
- Background images can appear just once or be repeated across the background of the box.
- You can create image rollover effects by moving the background position of an image.
- To reduce the number of images your browser has to load, you can create image sprites.

### ***Practical Information***

- Search engine optimization helps visitors find your sites when using search engines.
- Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there.
- To put your site on the web, you will need to obtain a domain name and web hosting.
- FTP programs allow you to transfer files from your local computer to your web server.
- Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website tools (to save you writing them from scratch).

### ***HTML5 video and audio***

The ```<video>``` and ```<audio>``` elements allow us to embed video and audio into web pages. 
```
<video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```

### ***The HTMLMediaElement API***
Part of the HTML5 spec, the ```HTMLMediaElement``` API provides features to allow you to control video and audio players programmatically — for example ```HTMLMediaElement.play()```, ```HTMLMediaElement.pause()```, etc. This interface is available to both ```<audio>``` and ```<video>``` elements, as the features you'll want to implement are nearly identical. Let's go through an example, adding features as we go.