# Hello Welcome To My Page :)

**Chapter 15**

**Layout**

In this chapter we are going to look at how to control where each element sits on a page and how to create attractive page layouts.

This involves learning about how designing for a screen can be different to designing for other mediums (such as print).

 In this chapter we will:

- Explore different ways to position elements using normal flow, relative positioning, absolute positioning and floats.

- Discover how various devices have different screen sizes and resolution, and how this affects the design process.

- Learn the difference between fixed width and liquid layouts, and how they are created.

- Find out how designers use grids to make their page designs look more professional.

-----

**Key Concepts in Positioning Elements**

**Building Blocks**

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

- Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.

**Block-level elements**

- **start on a new line**

  - Examples include:

    - < h1 > < p > < ul > < li >

**Inline elements**

- **flow in between surrounding text**

  - Examples include:

    - < img > < b > < i >

--------

**Floating Elements** 

![](https://i0.wp.com/css-tricks.com/wp-content/uploads/2021/03/web-text-wrap.png?resize=540%2C270&ssl=1)


**Float**

The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

Anything else that sits inside the containing element will flow around the element that is floated.

When you use the float 
property, you should also use the width property to indicate how wide the floated element should be. If you do not, results can be inconsistent but the box is likely to take up the full width of the containing element (just like it would in normal flow).





-----

**Screen Sizes**

Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

- When designing for print, you always know the size of the piece of paper that your design will be printed on. However, when it comes to designing for the web, you are faced with the unique challenge that different users will have different sized screens.

- Since computers have been sold to the public, the size of screens has been steadily increasing. This means that some people viewing your site might have 13 inch monitors while others may have 27+ inch monitors.

- The size of a user's screen affects how big they can open their windows and how much of the page they will see. There are also an increasing number of handheld devices (mobile phones and tablets) that have smaller screens.

----

**Screen Resolution**

Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

- Most computers will allow owners to adjust the resolution of the display or the number of pixels that are shown on the screen. For example, you can see the options to change the screen size from 720 x 480 pixels up to 1280 x 800 pixels.

- It is interesting to note that the higher the resolution, the smaller the text appears. Many mobile devices have screens that are higher resolution than their desktop counterparts.

**Page Sizes**

Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).
