CSS : Cascading Style Sheet

- W3C standard ,which is used to provide look and feel to the webpage.

- Latest version of css is css3

- Css Provides you some set of predefined properties and their respective value
  through we can able to design our webpage.

- We can apply style to our page using following three ways

  # 1. Inline Style :

  ***

  - This style is applied using style attribute of the tag.

  - Style attribute is the common attribute and it is available for every tag.

  - this style is used when we require to provide style to aparticular tag.

  - inline style working on element level.
  - Example:

     <body style="background-color:red">
          <p style="color:white">This is First Paragraph</p>
          <p style="color:yellow">This is Second Paragraph</p>
     </body>

  - Disadvantage : Difficult to maintain page consistency.

  # 2. Internal Style :

  ***

  - This style is applied using <style></style> tag inside <head></head> tag.

  - We use this style when we need to provide same style to more than one element in a page.

  - Internal style is working on page level.

  - We are providing style to different elements using selectors.

  - ## Selectors :

    - These are the identifiers which will use to identify html elements on which we are trying to apply style.

    - syntax:
      selector{
      property : value;
      property : value;
      }

    - There are diffrent type of selectors we are using in CSS.

      A. Element Selectors :

      - Here we are selecting html element through their name.

      - <html>
           <head>
              <style>
                 h1{
                   color : blue;
                 }
                 p{
                     color: red;
                 }
              </style>
           </head>
           <body>
              <h1>Heading1</h1>
              <h1>Heading2</h1>
              <p>paragraph1</p>
              <p>paragraph2</p>
           <body>
        </html>

    B. Id Selectors :

    -Example :
    <html>
    <head>
    <style>
    h1{
    color : blue;
    }
    p{
    color: red;
    }
    #p1{
        color: green;
    }
    </style>
    </head>
    <body>
    <h1>Heading1</h1>
    <h1>Heading2</h1>
    <p>paragraph1</p>
    <p id="p1">paragraph2</p>
    <p>paragraph3</p>
    <p>paragraph4</p>
    <body>
    </html>

  C. Class Selectors :

  - We use class select when we require different element having same style.

  - Example:

    .c1{
    font-size:30px ;
    border:2px solid green;
    padding:10px;
    display:block;
    }

    <p class="c1">paragraph6</p>
    <h1 class="c1">Heading3</h1>
    <a href="#" class="c1">this is a link</a>

  D. Universal Selector

  \*{

  }

  - When we need to apply common style to all elements then we can use universal selector.

# 3.External Style sheet

- This a file_name.css file ,which is called external stylesheet.

- In this file we put all style definitions.

- The page which will link this style sheet ,then all the style definition ,which
  matched for that page will applied.

- We are using external style sheet for maintaining whole website.

- It is very helpfull to maintain consisten look and feel of the complete website.

- We can use this style sheet to more that one page ,for maintaining similar style.

- It work on page Level.

- style.css -> stylesheet

- <link href="path of stylesheet" rel="stylesheet" type="text/css" />

# => Properties in CSS

1. Background

   background-color :  
   background-position:

2. Border

# Color in CSS

---

Color Coding Standards :

1. Color Names

2. RGB (Red,Green,Blue)

   rgb(0,0,0); -> Black
   rgb(25,255,255); -> White

3. Hexadecimal

   #000000 -> Black

   #FFFFFF -> White

4. Hexadecimal Short Notation

   #000

5. HSL (hue,Saturation , Lightness)

6. CMKY (Cyan,Magenta,Key ,Yellow)

You can use Color Picker for Selecting desired color.

https://htmlcolorcodes.com/color-picker/

https://www.w3schools.com/colors/colors_picker.asp

- To apply Transparency we use the following :

  rgba(0,0,0,0.0)
  rgba(0,0,0,1.0)

- 1. Background :

  background-color
  background-image : url('')

  background-repeat :
  no-repeat
  repeat
  repeat-x
  repeat-y
  background-attachment
  background-position
  background (shorthand property)
