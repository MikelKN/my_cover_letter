# My-First-Web-Design
Intermediate HTML and CSS

In this project, I use Basic knowledge of CSS and HTML to build my personal profile.  

To see the Project Design, Please click on the link -> https://mikelkn.github.io/web_design/
---------------------------------------------------------------
# Project 2 Intermediate HTML and CSS: Building My Personal profile.


## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [What I learned](#what-i-learned)
  - [Introductory CSS.](#introductory-css)
  - [Intermediate CSS.](#intermediate-css)
  - [Introduction to Web Design.](#introduction-to-web-design)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
Introductory and intermediate Cascading Style Sheets(CSS).This was built from a beginners section of the Web Development Course from Udemy 2022
Instructor: Angela Yu.

- Only purpose is to style Markup languages such as HTML code
- Used a Design inspiration from Sean Halpin (https://images.app.goo.gl/1tvTVow3EvDDV3MU9 )

### Links

- Project URL:
- Live Site URL:

## What I learned
### Introductory CSS.
- Inline CSS
- Internal CSS using <style> Tag - Implement a style attribute throughout/across all the project.
  - Can be used to override original styles.
  ```
  <!--This code applies a background: Blue, to the entire body of the website body
  Also Changes the styles of all the <h1> headings --> comments
  <style>
    body{
      background-color: blue;
    }
    h1 {
      font size: 10px;
      color: red;
      font style: Monospace;
    }

  </style>
  ```
- Border Styles : Syntax follows clockwise representation(border style: top left bottom right)
- External CSS :
  - Create a new folder where the styles.css file will reside at the same hierarchical level as the .html file.
  - Create new link in the head to recognize and point to the syles.css file.
  ```
  <link rel='stylesheet' href="location of your styles.css file- css/styles.css">
  ```
- The CSS Syntax : Best practice: Have all properties in Alphabetical order.
  ```
  h1 {
    color : red;
    font-size: 200px;
  }
  ```
  - CSS Selectors : Overwrite other styles in the stylesheet applied to the same element since they are more specific that tag selectors.
    - class - Can be used multiple times throughout the project. [Analogous to Name]
            - We can also use more than one class for one particular element eg class example_class and    Circular
    - Pseudo-class: eg Hover state - What happens when you hover over the element.
    - ID - Can only be used on a single item in a project.[Analogous to Passports]
    ```
    .example_class {
      color : red;
      font-size: 200px;
    }
    #example_id{
      text-align : Center;
    }
    ```
### Intermediate CSS.
- Building or Creating Favicons (Favorite Icons) - what show up on the browser bar.
- Creating HTML Divisions or containers.
- CSS Box Model : Understanding Margins, Borders and Paddings.
  - Margin: Outside the border and it is the space between different items - Pushes contents/Divs away from each other.;
  - Border : The outmost part of a Divisions - Outlines
  - Padding : The space between the border and the content inside the div
- CSS Display Properties:
  - Block display: Takes up the whole length of screen eg Paragraph, all Headers, Divisions, Lists and lists items, Forms.
  - Inline Display Element: Only takes up as much element as it needs to be. eg Span, Images, Anchors Tags
    - <SPAN> tag to add/concatenate 2 different paragraphs on the same line - Can be nested or stand-alones however widths can't be changed.
  - Can change all block elements to Inline elements and Vice Versa using the ```display: Inline or Block```;
  - Can also use ```display: Inline-Block;``` for the best of both world have all divs appear on same line adjacent to each other.
  - Disappearance: ```display: None;```  or ```Visibility: hidden;``` to hide things in a website.
- Positioning: Static (default); Relative ; Absolute
    - Relative: Moves it to the specified *coordinate* eg ```img{position: relative; coordinate:30px}``` - Will overlay whatever on its path.
    - Absolute: Take the element out of the HTML flow-affects the other divs on screen and moves items *away from* a specified coordinate
- Centering: using ```text-align``` or ```margin: 0 auto 0 auto``` if it is a block lement with a width set;
### Introduction to Web Design.
- **Color Theory**: Be aware of the mood the color conveys.
    - Colors and their Moods: Red: Love, Energy, intensity; Yellow: Joy, Intellect, Attention grabbing;  Green: Freshness, Growth, Safety(Food); Blue: Stability, serenity, Trust (Finance). Purple: Royalty, Femininity, Wealth.
    - Analogous Color palettes: Colors close in colors: Navigation bar, body, Logos and their background.
    - Complementary Color Palette: Provides color pop; Not good for Text; Best for Logos.
- **Typography** : Serif : Traditional ; **Sans-serif : Modern, Friendly, approachable, novel, contemporary** ; *rule of thumbs: stick to just 2 fonts per design and should be of almost similar in fonts*
- **User Interface** : Hierarchy : Colors, Size, Layout(40 - 60 xters per line), Alignment(less is best), **White space** , Audience.
- **User Experience(UX) Design**: Simplicity, Consistency, Reading Patterns(F and Z -Layout pattern), *All platform Design*, **Dark Patterns: Don't use your powers for Bad**.

## Useful Tools
- HTML5
- Introductory Cascading Style Sheets (CSS)
- Intermediate CSS

## Continued development
- Make the system adapt and scaled to different screen or Applications like Mobile phones, Ipads etc

## Useful resources

- [CSS-MDN] https://developer.mozilla.org/en-US/docs/Web/CSS - CSS Documentation
  - CSS color types: Provides valid CSS colors names and Hex codes.
- [Colorhunt] https://colorhunt.co/ - To find and use beautiful color palettes (with Hex values or just color names) for your website projects
- [Pesticide] https://chrome.google.com/webstore/detail/pesticide-for-chrome-with/neonnmencpneifkhlmhmfhfiklgjmloi?hl=en-US - To make your website entries into visual box representation
- [Favicons] https://www.favicon.cc/ - Upload, Generate and Build  Favicons.
- Google Developers tools [Right Click > INSPECT]
- Lorem Ipsum generator. com

## Author
My different account profiles on:
- FreeCodeCamp - [@MikelD](https://www.freecodecamp.org/MikelD)
- Frontend Mentor - [@MikelKN](https://www.frontendmentor.io/profile/MikelKN)
- Kaggle - [@mikelkn](https://www.kaggle.com/mikelkn)
- LinkedIn - [@mikelngueajio](https://www.linkedin.com/in/mikelngueajio/)


## Acknowledgments
