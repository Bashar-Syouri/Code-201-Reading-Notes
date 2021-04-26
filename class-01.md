#  Welcome  
![HTML](https://elzero.org/wp-content/uploads/2019/06/learn-html4.png)




## - Chapter 1 

**STRUCTURE**

![structure](https://slideplayer.com/15204885/92/images/slide_2.jpg)

#### We come across all kinds of documents every day of our lives. Newspapers, insurance forms, shop catalogues... the list goes on.

#### Many web pages act like electronic versions of these documents. For example, newspapers show the same stories in print as they do on websites; you can apply for insurance over the web; and stores have online catalogs and e-commerce facilities. 


In all kinds of documents, structure is very important in helping readers to understand the messages you are trying to convey and to navigate around the document. So, in order to learn how to write web pages, it is very important to understand how to structure documents. In this chapter you will:-

● See how HTML describes the structure of a web page
● Learn how tags or elements are added to your document
● Write your first web page



## How Pages Use Structure 


- Think about the stories you read in a newspaper: for each story, there will be a headline, some text, and possibly some images. If the article is a long piece, there may be subheadings that split the story into separate sections or quotes from those involved. Structure helps readers understand the stories in the newspaper.

- The structure is very similar when a news story is viewed online (although it may also feature audio or video). This is illustrated on the right with a copy of a newspaper alongside the corresponding article on its website.

- Now think about a very different type of document — an insurance form. Insurance forms often have headings for different sections, and each section contains a list of questions with areas for you to fill in details or checkboxes to tick. Again, the structure is very similar online.


### HTML Uses Elements to Describe the Structure of Pages 


There are several different elements. Each element has an opening tag and a closing tag.

**Tags**


Tags act like containers. They tell you something about the information that lies between their opening and closing tags.

- **A Closer Look at tags**

![opening and closing tags](https://res.cloudinary.com/zheisey/image/upload/f_auto/v1573769310/zac-heisey.com/lessons/html-element-syntax.jpg)

 - Opening Tag <P>

   - The characters in the brackets indicate the tag's purpose. 
   - For example, in the tags above the p stands for paragraph.

- The closing tag has a forward 
slash after the the < symbol.


- Closing Tag </P>
  
  - The terms "tag" and "element" 
are often used interchangeably.

  - Strictly speaking, however, an element comprises the opening.
  

- tag and the closing tag and any  content that lies between them.


### Attributes Tell Us More About Elements

Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

- The attribute name indicates what kind of extra information you are supplying about the element's content. It should be written in lowercase.

- The value is the information or setting for the attribute. It should be placed in double quotes. Different attributes can have different values.

- Here an attribute called lang is used to indicate the language used in this element. The value of this attribute on this page specifies it is in US English.

---------------

#  Body, Head & Title 
![body, head & title](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/html-images-df.jpg)



## < body > 
You met the < body > element in the first example we created. Everything inside this element is shown inside the main browser window.



## < head > 
Before the < body > element you will often see a < head > element. This contains information about the page (rather than information that is shown within the main part of the browser window that is highlighted in blue on the opposite page). You will usually find a < title > element inside the < head > element.

## < title > 
The contents of the < title > element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).

-----------------------------------



## - Chapter 8 


![extra markup](https://slideplayer.com/12052645/69/images/slide_1.jpg)

**Extra Markup**

#### At this point, we have covered the main tags that fit nicely into groups and sections. 

##### - In this chapter, we will focus on some helpful topics that are not easily grouped together. You will learn about:


 - The different versions of HTML and how to indicate which version you are using

  -  How to add comments to your code

  - Global attributes, which are attributes that can be used on any element, including the class and id attributes 

 - Elements that are used to group together parts of the page where no other element is suitable

- How to embed a page within a page using iframes

- How to add information about the web page using the <meta> element

- Adding characters such as angled brackets and copyright 
symbols


## Block Elements & Inline Elements 

![block and inline elements](https://ictacademy.com.ng/wp-content/uploads/2017/10/inline-block-and-positioning-in-css-4-638.jpg)

**Block Elements**

Some elements will always appear to start on a new line in the browser window. These are known as block level elements. 

---------


**Inline Elements**

Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.


---------

**- Chapter 17**
![HTML5 Layout](https://slidetodoc.com/presentation_image_h/0040e0df67c799a15c4676d1f0725e2f/image-2.jpg)


**Traditional HTML Layouts**

For a long time, web page authors used <div> elements to group together related elements on the page (such as the elements that form a header, an article, footer or sidebar). Authors used class or id attributes to indicate the role of the <div> element in the structure of the page.

![](https://csharpcorner.azureedge.net/UploadFile/b5be7f/working-with-new-semantic-elements-in-html5-along-with-html/Images/Html%20Basic%20Structure%20Image.png)

On above you can see a layout that is quite common (particularly on blog sites).

At the top of the page is the header, containing a logo and the primary navigation.

Under this are one or more articles or posts. Sometimes these are summaries that link to individual posts.

There is a side bar on the righthand side (perhaps featuring a search option, links to other recent articles, other sections of the site, or even ads).

When coding a site like this, developers would usually put these main sections of the page inside <div> elements and use the class or id attributes to indicate the purpose of that part of the page.

-----

**New Html5 Layout Elements**

HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors using them already.

![](https://slidetodoc.com/presentation_image_h/0040e0df67c799a15c4676d1f0725e2f/image-8.jpg)

This example has exactly the same structure as seen on the previous page. However, many of the <div> elements have been replaced by new HTML5 layout elements.

For example, the header sits inside a new <header> element, the navigation in a <nav> element, and the articles are in individual <article> elements.

The point of creating these new elements is so that web page authors can use them to help describe the structure of the page. For example, screen reader software might allow users to ignore headers and footers and get straight to the content. Similarly, search engines might place more weight on the content in an <article> element than that in the <header> or <footer> elements. I think you will agree that it also makes the code easier to follow.
----- 
**Headers & Footers**
< header > < footer >

The < header > and < footer > elements can be used for:

● The main header or footer that appears at the top or bottom of every page on the site.

● A header or footer for an individual <article> or <section> within the page.

![](https://miro.medium.com/max/524/1*2WhcT-zGk8qg4mM2J_Kbhw.png)

-----


**Navigation**
< nav >

The < nav > element is used to contain the major navigational blocks on the site such as the primary site navigation.

![Navigation](https://cdn-images-1.medium.com/max/665/1*v_rVmy4NedLx9laqIoBx0g.png)

Going back to our blog example, if you wanted to finish an article with links to related blog posts, these would not be counted as major navigational blocks and therefore should not sit inside a <nav> element.

At the time of writing, some of the developers that were already using HTML5 decided to use the < nav > element for the links that appear at the bottom of every page ( links to things like privacy policy, terms and conditions and accessibility information ). Whether this will be widely adopted is still yet to be seen.
 

------

**Articles**
< article >

The < article > element acts as a container for any section of a page that could stand alone and potentially be syndicated.

This could be an individual article or blog entry, a comment or forum post, or any other independent piece of content.

If a page contains several articles ( or even summaries of several articles), then each individual article would live inside its own <article> element.

The <article> elements can even be nested inside each other. For example, a blog post might live inside one < article > element and each comment on the article could live inside its own child <article> element.

------


**Asides**
< aside >

The <aside> element has two purposes, depending on whether it is inside an < article > element or not.

![aside](https://i.ytimg.com/vi/xfwjbZU0YZI/maxresdefault.jpg)

When the <aside> element is used inside an < article > element, it should contain information that is related to the article but not essential to its overall meaning. For example, a pullquote or glossary might be considered as an aside to the article it relates to.

When the <aside> element is used outside of an < article > element, it acts as a container for content that is related to the entire page. For example, it might contain links to other sections of the site, a list of recent posts, a search box, or recent tweets by the author.

------

**Sections**
< section >

The <section> element groups related content together, and typically each section would have its own heading.

![section](https://i.ytimg.com/vi/cRqcXjpyce0/maxresdefault.jpg)

For example, on a homepage there may be several < section > elements to contain different sections of the page, such as latest news, top products, and newsletter signup.

Because the <section> element groups related items together, it may contain several distinct < article > elements that have a common theme or purpose.

Alternatively, if you have a page with a long article, the < section > element can be used to split the article up into separate sections.

The <section> element should not be used as a wrapper for the entire page ( unless the page only contains one distinct piece of content ). If you want a containing element for the entire page, that job is still best left to the < div > element.

---------


## - Chapter 18

**Process & Design**

![process & design](https://www.mypsdtohtml.com/assets/img/responsive_flow.png)

This section discusses a process that you can use when you are creating a new website.

It looks at who might be visiting your site and how to ensure 
the pages feature the information those visitors need. It also 
covers some key aspects of design theory to help you create 
professional looking sites. In this chapter, we will look at:

● How to understand the audience your site may attract and 
what information they will expect to find on it

● How to organize information so that visitors can find what 
they are looking for

● Design theory for presenting information in a way that 
helps visitors achieve their goals

● Design tips to help you create more attractive and 
professional sites


**Who is the Site For?**

Every website should be designed for the  target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.

It can be helpful to ask some questions about the people you would expect to be interested in the subject of your site.
If you ask a client who a site is for, it is not uncommon for them to answer "the entire world."

Realistically, it is unlikely to berelevant to everyone. If your site sells light bulbs, even though most people using a computer 
probably use light bulbs, they are not likely to order them from someone in a different country.

Even if the site has a wide appeal, you can still think about the demographics of a sample of the target audience. 

**Target Audience: individuals**

● What is the age range of your target audience?

● Will your site appeal to more women or men? What is the mix?

● Which country do your visitors live in?

● Do they live in urban or rural areas?

● What is the average income of visitors?

● What level of education do they have?

● What is their marital or family status?

● What is their occupation?

● How many hours do they work per week?

● How often do they use the web?

● What kind of device do they use to access the web?

**Target Audience: Companies**

● What is the size of the company or relevant department?

● What is the position of people in the company who visit your site?

● Will visitors be using the site for themselves or for someone else?

● How large is the budget they control?

**Visual hierarchy**

Most web users do not read entire pages. Rather, they skim to find information. You can use contrast to create a visual hierarchy that gets across your key message and helps users find what they are looking for.

**SIZE**
Larger elements will grab users' attention first. For this reason it is a good idea to make headings and key points relatively large.

**COLOR**
Foreground and background color can draw attention to key messages. Brighter sections tend to draw users' attention first.

**Style**
An element may be the same size and color as surrounding content but have a different style applied to it to make it stand out.

**Visual hierarchy** refers to the order in which your eyes perceive what they see. It is created by adding visual contrast between the items being displayed. Items with higher contrast are recognized and processed first.

**Images**
Images create a high visual contrast and often attract the eye first. They can be used to draw attention to a specific message within the page. In some cases, the right image can succinctly reveal more than an entire page of text.

The effect of a well-designed visual hierarchy is largely subliminal. Achieving a good hierarchy requires balance; if nothing stands out a site can be rather uninteresting, and if too many aspects are competing for your attention it can be hard to find the key messages. This example has a clear hierarchy which addresses the needs of visitors to the site.

**Summary**

PROCESS & Design

- It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.

- Site maps allow you to plan the structure of a site.

- Wireframes allow you to organize the information that will need to go on each page.

- Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.

- You can differentiate between pieces of information using size, color, and style. 

- You can use grouping and similarity to help simplify the information you present.



**To Learn More Visit** [Link](https://wtf.tw/ref/duckett.pdf)



&copy; HTML 2021.
