# Month 2, Week 2: Progress Update at Altschool Africa School of Engineering 📚💻

This week marked an exciting continuation of my HTML learning journey, where we delved deeper into essential concepts around embedding content, sectioning, text formatting, interactive elements, and the use of semantic vs. non-semantic markup. Let’s break down the key learnings!

## 1. Embedding Content

Embedding external content into HTML documents allows us to enrich our web pages with dynamic media from external sources. Here are three key elements used for embedding:

- `<iframe>`: This element allows you to embed external web content (like videos or interactive maps) inside a webpage.
  ```html
  <iframe src="https://www.josephibeh.com" width="600" height="400"></iframe>

-<embed>: Used for embedding multimedia files like audio or video into the document
<embed src="video.mp4" type="video/mp4" width="400" height="300">

-<object>: Designed to embed external resources such as PDFs, Flash files, or other multimedia formats.
<object data="file.pdf" type="application/pdf" width="600" height="400"></object>

These embedding techniques add dynamic functionality to webpages, improving user engagement.

2. Sectioning and Grouping Content
HTML5 introduced semantic elements that define the structure of a document in a more meaningful way. This improves readability, accessibility, and SEO. Here's what we covered:

<header>: Represents the introductory section of a document or a section, usually containing navigation links, a logo, or headings.

<header>
  <h1>Welcome to My Blog</h1>
</header>

<nav>: Defines the navigation links of a website.
<nav>
  <a href="/home">Home</a> | <a href="/about">About</a>
</nav>

<main>: Specifies the main content of a document, excluding headers, footers, or navigation.

<main>
  <article>
    <h2>Latest Article</h2>
    <p>This is the content of the article</p>
  </article>
</main>

<footer>: Defines the footer section, often containing copyright information or additional navigation.

<footer>
  <p>&copy; Joseph ibeh 2024</p>
</footer>

<section>: Defines a thematic grouping of content, like chapters or sections of a document.

<section>
  <h2>Section Title</h2>
  <p>This is a section of related content</p>
</section>

<article>: Represents a self-contained unit, such as a blog post, article, or forum entry.

<article>
  <h2>Blog Post Title</h2>
  <p>This is the content of the blog post...</p>
</article>

<aside>: Contains content related to the main content but not essential to the flow, like sidebars.

<aside>
  <p>This is related information...</p>
</aside>

<figure> and <figcaption>: These elements are used to group media, like images, with a caption to describe them.

<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>This is an image of...</figcaption>
</figure>

Using semantic elements improves the structure of web pages, making them easier for both users and search engines to interpret.


3. Text Formatting Tags
Text formatting in HTML allows us to control the appearance of the text. Here are the key tags we explored:

Headings (<h1> to <h6>): Define different levels of headings, with <h1> being the highest priority.
<p>: Paragraph tag used to define blocks of text.
<span>: Inline container, often used for styling small sections of text.
<strong> and <b>: Bold text, with <strong> implying importance.
<em> and <i>: Italic text, with <em> conveying emphasis.
<u>: Underlined text.
<strike>: Strikethrough text.
These tags allow us to format text, making the content more readable and visually appealing.

4. Interactive Elements
HTML provides several elements to create interactive forms for user input:

-<form>: Defines a form for user input

<form action="/submit" method="POST">
  <input type="text" name="name">
  <input type="submit" value="Submit">
</form>

<input>: Creates an input field for various types of data (text, email, password, etc.).
<textarea>: Creates a larger, multi-line text input area.
<select>: Creates a dropdown menu for selecting options

<select name="options">
  <option value="1">Option 1</option>
  <option value="2">Option 2</option>
</select>

<button>: Defines a clickable button.
<button type="submit">Submit</button>

These elements help create engaging user interfaces, allowing users to input and interact with content.

5. Semantic vs. Non-Semantic Markup
Semantic Markup: Uses meaningful tags to provide context and structure to a webpage. Examples include <header>, <nav>, <main>, and <section>. This helps improve accessibility and SEO.

Non-Semantic Markup: Uses generic tags like <div> or <span> without providing any inherent meaning to the content. They are primarily styled or scripted for their purpose.

6. Scripts and Styles
Finally, we explored how to incorporate external resources like JavaScript and CSS into our HTML documents:

<script>: Embeds or references JavaScript code in the HTML file.

<script src="script.js"></script>
<style>: Embeds CSS styles directly within the HTML document.
html
Copy code
<style>
  body {
    background-color: lightblue;
  }
</style>
<link>: Links to an external CSS stylesheet.

<link rel="stylesheet" href="styles.css">
These elements allow us to add behavior and design to our HTML structure, enhancing both aesthetics and functionality.

I’m excited to continue this journey as I gain a deeper understanding of web development and its building blocks! Stay tuned for more updates.

![Week 2 week_2 Progress](https://github.com/Joseph-Ibeh/AltSchool_learning_journey/blob/main/images/random%20use.jpg)

