# Hello To My Page


**Domain Modeling**

*Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.*
*A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.*

* Define a constructor and initialize properties
*To define the same properties between many objects, you'll want to use a constructor function.*

**Generate random numbers**

*To model the random nature of user behavior, you'll need the help of a random number generator. Fortunately, the JavaScript standard library includes a Math.random() function for just this sort of occasion.*

>Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.
>Some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the new keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the this variable within methods so you can access the object's properties and methods from inside.

-------

**Chapter 6**


 **Tables**

 There are several types of information that need to be displayed in a grid or table. For example: sports results, stock reports, train timetables.

 When representing information in a table, you need to think in terms of a grid made up of rows and columns (a bit like a spreadsheet). In this chapter you will learn how to: 

- Use the four key elements for creating tables

- Represent complex data using tables

- Add captions to tables


**What's a Table?**

*A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results*

**Basic Table Structure**

**< table >**

The < table > element is used to create a table. The contents of the table are written out row by row.


**< tr >**

You indicate the start of each row using the opening < tr > tag. (The tr stands for table row.)  

It is followed by one or more < td > elements (one for each cell in that row). 

At the end of the row you use a closing < /tr > tag.

**< td >**

Each cell of a table is represented using a < td >element. (The td stands for table data.)

At the end of each cell you use a closing < /td > tag.


**Table Headings** 

**< th >**

The < th > element is used just like the < td > element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)

Even if a cell has no content, you should still use a < td > or < th > element to represent the presence of an empty cell otherwise the table will not render correctly. (The first cell in the first row of this example shows an empty cell.)

Using < th > elements for headings helps people who use screen readers, improves the ability for search engines to index your pages, and also enables you to control the appearance of tables better  when you start to use CSS.


You can use the scope attribute on the < th > element to indicate whether it is a heading for a column or a row. It can take the values: row to indicate a heading for a row or col to indicate a heading for a column.


**Spanning ColumnS and Rows:**

You can make cells of a table span more than one row or column using the rowspan and colspan attributes.

![]( https://t4tutorials.com/wp-content/uploads/2017/02/rowspan-and-colspan-in-html.png)


![]( https://flylib.com/books/2/631/1/html/2/images/08fig19.jpg)


For long tables you can split the table into a thead, tbody, and tfoot

![]( https://slideplayer.com/slide/15539438/93/images/19/LONG+TABLES+%3Cthead%3E+%3Ctr%3E+%3Cth%3EDate%3C%2Fth%3E+%3Cth%3EIncome%3C%2Fth%3E+%3Cth%3EExpenditure%3C%2Fth%3E+%3C%2Ftr%3E+%3C%2Fthead%3E+%3Ctbody%3E...%3C%2Ftbody%3E+%3Ctfoot%3E...%3C%2Ftfoot%3E.jpg)
![]( https://i.ytimg.com/vi/q1nw4oFUuD8/maxresdefault.jpg)
