# Class 2 Notes

## **Basics of HTML, CSS, & JS**

![HTML, CSS, JS](./images/htmlcssjava.png)

### [1] <u>HTML</u> 💀

- Why is it important to use semantic elements in our HTML?

> So that the browser knows how to display it correctly.

- How many levels of headings are there in HTML?

> `h1` `h2` `h3` `h4` `h5` `h6`

- What are some uses for the `<sup>` and `<sub>` elements?

> You will occasionally need to use superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning. The `<sup>` and `<sub>` elements handle this job. For example:

> `<p>`My birthday is on the 25`<sup>`th`</sup>` of May 2001.`</p>``<p>` 

>Caffeine's chemical formula is
  C`<sub>`8`</sub>`H`<sub>`10`</sub>`N`<sub>`4`</sub>`O`<sub>`2`</sub>`.`</p>`

>`<p>`If x`<sup>`2`</sup>` is 9, x must equal 3 or -3.`</p>`

The output:

> <p>My birthday is on the 25<sup>th</sup> of May 2001.</p>
<p>

> Caffeine's chemical formula is C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>.
</p>

> <p>If x<sup>2</sup> is 9, x must equal 3 or -3.</p>.

- When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?

> If providing the expansion in addition to the abbreviation makes little sense, and the abbreviation or acronym is a fairly shortened term, provide the full expansion of the term as the value of `title` attribute.

### [2] <u>CSS</u> ✨

- What are ways we can apply CSS to our HTML?

> Externally, Internally, or Inline

- Why should we avoid using inline styles?

> It is the least efficient implementation of CSS for maintenance

- Review the block of code below and answer the following questions:

    1. What is representing the selector?
      > `h2`

    1. Which components are the CSS declarations?
      > Anything between the curly brackets. This is also called the "Declaration Block"

    1. Which components are considered properties?
      > color: black;
      > padding: 5px;

``
h2 {
     color: black;
     padding: 5px;
   }
``

### [3] <u>JavaScript</u> 💥

- What data type is a sequence of text enclosed in single quote marks?

> A string

- List 4 types of JavaScript operators.

> +, -, *, /

- Describe a real world Problem you could solve with a Function.

> Converting Celsius into Fahrenheight and vise versa.

#### *Making Decisions In Your Code – Conditionals.*

- An if statement checks a 'conditon' and if it evaluates to 'true', then the code block will execute.

- What is the use of an else if?
List 3 different types of comparison operators.
  
  1. === and !== — test if one value is identical to, or not identical to, another.

  1. < and > — test if one value is less than or greater than another.

  1. <= and >= — test if one value is less than or equal to, or greater than or equal to, another.

- What is the difference between the logical operator `&&` and `||`?

> && — AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.

> || — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.

------
Reference:

[1] : [Intro to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/)

[1] : [HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

[1] : [HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

[2] : [How CSS is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

[3] : [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

[3] : [Making Decisions In Your Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

❗❗❗ Bookmark and Review ❗❗❗
- https://chris.beams.io/posts/git-commit/