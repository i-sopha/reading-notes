# Class 1 Notes 📃

![Some Motivation](./images/motivation.png)

## [1] **Getting Started**

- Compose a short poem describing how HTTP sends data between computers.

> Where art thou data

> client to server, server to client

>requesting

> always requesting

> always answering


- Describe how HTML, CSS, and JS files are “parsed” in the browser.

> When a web browser receives HTML, CSS, and JavaScript files, it must "parse" them in order to display the web page correctly.

> HTML: When a browser receives an HTML file, it will parse the HTML file, line by line, from top to bottom. The browser will look for HTML tags, such as `<body>`, `<head>`, and `<title>`, and will interpret those tags to display the page in the correct way.

> CSS: When the browser receives a CSS file, it will parse the CSS file, line by line, from top to bottom. The browser will look for CSS rules, such as font-size, background-color, and width, and will apply those rules to the elements on the page, in order to style the page correctly.

> J`avaScript: When the browser receives a JavaScript file, it will parse the JavaScript file, line by line, from top to bottom. The browser will look for JavaScript code, such as functions, variables, and statements, and will execute that code in order to make the page interactive.

How can you find images to add to a Website?

- How can you find images to add to a Website?

>   1. Search Google Images using the keyword “Creative Commons” or “Public Domain” to find images that are allowed to be used without permission.
>   1. Use free stock photo websites such as Unsplash, Pexels, or Pixabay.
>   1. Use Creative Commons or public domain images from Flickr or Wikimedia Commons.
>   1. Take your own photos or create your own artwork.
>   1. Use stock photo websites such as Shutterstock, Getty Images, Adobe Stock, or iStock.
>   1. Ask permission from the copyright holder if you find an image you would like to use.

- How do you create a String vs a Number in JavaScript?

> String - To create a string in JavaScript, you need to use quotation marks around the string's value.

`let myString = "This is a string";`

> Number - To create a number in JavaScript, you simply assign the number without any quotations

`let myNumber = 42;`

- What is a Variable and why are they important in JavaScript?

> A variable is a named container that holds a value. Variables are important in JavaScript because they enable us to store, access, and manipulate data within our programs. Variables allow us to easily change values, store information, and create logic in our programs.

## [2] **Introduction to HTML**

- What is an HTML attribute?
Describe the Anatomy of an HTMl element.

> Attributes contain extra information about the element that won't appear in the content

> ![HTML Anatomy](./images/htmlanatomy.png)

- What is the Difference between `<article>` and `<section>` element tags?

> Both are semantic tags. The article tag is used for wrapping an autonomous content on a page. A content is autonomous if it can be removed from the page and put on some another page. The section tag is similar to the div tag, but it is more meaningful since it wraps logical groups of related conten

- What Elements does a “typical” website include?

> `<header>` `<body>` `<main>` `<footer>` and many more..

- How does metadata influence Search Engine Optimization?

> Metadata are not not displayed on the page but they are used by search engines (such as Google) to get keywords and other information and displays/boosts them when a search is executed.

- How is the `<meta>` HTML tag used when specifying metadata?

> One way to use the `<meta>` tag is to specify the characer set that we can use in the document eg. `<meta charset="utf-8"/>`

## [3] **Miscellaneous**

### *How to start to design a Website.*

- What is the first step to designing a Website?

> Deciding in *detail* what you want to do.

- What is the most important question to answer when designing a Website?

> "What exactly do I want to accomplish?"

### *Semantics*

- Why should you use an `<h1>` element over a `<span>` element to display a top level heading?

> `<h1>` is a semantic element which will give the text it wraps around the role (or meaning) of a "top level heading on your page.

- What are the benefits of using semantic tags in our HTML?

>    1. Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
>   1. Screen readers can use it as a signpost to help visually impaired users navigate a page
>    1. Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
>    1. Suggests to the developer the type of data that will be populated
>    1. Semantic naming mirrors proper custom element/component naming

### *What is JavaScript?*

- Describe 2 things that require JavaScript in the Browser?

> JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else.

- How can you add JavaScript to an HTML document?

> With the `<script>` element.

-----

Reference:

[1] : [Getting Started](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/)

[1] : [How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[1] : [Website Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

[1] : [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

[2] : [Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

[2] : [HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[2] : [Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

[3] : [How to start to design a Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

[3] : [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

[3] : [What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)