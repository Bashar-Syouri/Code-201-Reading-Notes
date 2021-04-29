# Welcome to my page :)

**Chapter 5**

**IMAGES**

There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.

There are several things to consider when selecting and preparing images for your site, but taking time to get them right will make it look more attractive and professional.

In this chapter you will learn how to:
- Include an image in your web pages using HTML.
- Pick which image format to use.
- Show an image at the right size.
- Optimize an image for use on the web to make pages 
load faster.


![Images](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/html-images-df.jpg)


**Choosing Images for Your Site**

A picture can say a thousand words, and great images help make thedifference between an average-looking site and a really engaging one.


Images can be used to set the tone for a site in less time than it takes to read a description. If you do not have photographs to use on your website, there are companies who sell stock images; these are images you pay to use (there is a list of stock photography websites below). Remember that all images are subject to copyright, and you can get in trouble for simply taking photographs from another website.

If you have a page that shows several images (such as product photographs or members of a team) then putting them on a simple, consistent background helps them look better as a group.

**Images should...**

 - Be relevant
 - Convey information
 - Convey the right mood 
 - Be instantly recognisable 
 - Fit the color palette

**Stock photos**

[www.istockphoto.com](www.istockphoto.com)

[www.gettyimages.com](www.gettyimages.com)

[ww.veer.com](www.veer.com)

[www.sxc.hu](www.sxc.hu)

[www.fotolia.com](www.fotolia.com)



**Online extra**

We have provided an online gallery that helps you choose the right image for your website. You can find it in the tools section of the site accompanying this book.

------

**Storing Images on Your Site**

If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.

- As a website grows, keeping images in a separate folder helps you understand how the site is organized. 

- On a big site you might like to add subfolders inside the ***images*** folder. For example, images such as logos and buttons might sit in a folder called ***interface***, product photographs might sit in a page called ***products***, and images related to news might live in a folder called ***news***.

- If you are using a content management system or blogging platform, there are usually tools built into the admin site that allow you to upload images, and the program will probably already have a separate folder for image files and any other uploads.

------

**Adding Images**

**< i mg src="images/quokka.jpg" alt="A family of 
quokka" title="The quokka is an Australian  marsupial that is similar in size to the 
domestic cat." / >**



**< img >**

To add an image into the page you need to use an < img > element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:



**src**

This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. Here you can see that the images are in a child folder called images

**alt**

This provides a text description of the image which describes the image if you cannot see it.

**title**

You can also use the titleattribute with the < img > element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.






---------


**Height & Width of Images**

< img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" / >



You will also often see an < img > element use two other attributes that specify its size:

**height**
This specifies the height of the image in pixels.


**width**
This specifies the width of the image in pixels.


Images often take longer to load than the HTML code that makes up the rest of the page. It is, therefore, a good idea to specify the size of the image so that the browser can render the rest of the text on the page while leaving the right amount of space for the image that is still loading.

-------------


**Where to Place Images in Your Code**


Where an image is placed in the code will affect how it is displayed. Here are three examples of image placement that produce different results:

**1. before a paragraph**

The paragraph starts on a new line after the image.

**2. inside the start of a paragraph** 

The first row of text aligns with the bottom of the image.

**3. in the middle of a paragraph**

The image is placed between the words of the paragraph that it appears in.


Where you place the image in the code is important because browsers show HTML elements in one of two ways:

- **Block elements always appear on a new line.** 
Examples of block elements include the < h1 > and < p > elements.


- **Inline elements sit within a block level element and do not start on a new line.**
 Examples of inline elements include the < b >, < em >, and < img > elements.


 
