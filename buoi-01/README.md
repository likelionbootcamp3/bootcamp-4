# Week 1-1: HTML

## I. Introduction

1. What is HTML?

- HTML stands for HyperText Markup Language and is a standard markup language used to create and structure web content. HTML defines the structure and content of a web page, using a set of tags and attributes to describe the text, images, links, and other elements that make up a webpage. HTML is used in conjunction with other technologies, such as CSS and JavaScript, to create dynamic and interactive web pages.

2. Purposes of HTML

- To structure and organize content on the web, such as text, images, videos, and links.
- To define the semantic meaning of content, such as headings, paragraphs, lists, and other elements.
- To create a visually appealing and easy-to-use interface for users to interact with web content.
- To provide a way to embed multimedia elements, such as videos and images, into web pages.
- To allow web developers to create dynamic and interactive web pages using scripting languages, such as JavaScript.
- To provide a standardized format that can be rendered by web browsers, ensuring that web pages can be viewed on a variety of devices.
- To enable search engines to easily index and understand the content of web pages, improving search engine optimization (SEO).
- To create web applications and complex web-based systems that can be accessed from anywhere with an Internet connection.

## II. HTML Document Structure

Here is an example of a simple HTML document:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First HTML Page</title>
  </head>
  <body>
    <!-- Main content -->
  </body>
</html>
```

An HTML document has a basic structure that includes the following elements:

- **DOCTYPE declaration**: This line specifies the version of HTML being used in the document.
- **HTML element**: This is the root element of the document and contains all other elements.
- **Head element**: The head element contains meta information about the document, such as the title of the page, which is displayed in the browser tab, and links to CSS and JavaScript files.
- **Body element**: The body element contains the main content of the document, including text, images, videos, and other elements.

## III. HTML Elements

1. Heading:

```html
<h1>This is a level 1 heading</h1>
<h2>This is a level 2 heading</h2>
<h3>This is a level 3 heading</h3>
<h4>This is a level 4 heading</h4>
<h5>This is a level 5 heading</h5>
<h6>This is a level 6 heading</h6>
```

2. Paragraph:

```html
<p>This is a simple paragraph of text.</p>
```

3. Link:

```html
<a href="https://www.google.com">Go to Google</a>
```

4. Image:

```html
<img src="image.jpg" alt="An example image" />
```

5. List:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

6. Table:

```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1, Column 1</td>
    <td>Row 1, Column 2</td>
  </tr>
  <tr>
    <td>Row 2, Column 1</td>
    <td>Row 2, Column 2</td>
  </tr>
</table>
```

7. Form:

```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" />
  <br /><br />
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" />
  <br /><br />
  <input type="submit" value="Submit" />
</form>
```

## IV. Semantic Elements

Semantic elements are HTML elements that have a specific meaning and are used to define the structure and content of a web page. Semantic elements help improve the accessibility and maintainability of a web page, as they provide clear and meaningful information about the structure and content of the page to both users and search engines.

![Semantic Website Layout](https://res.cloudinary.com/practicaldev/image/fetch/s--oxQNUXvS--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/mpjv5mkzc9bc2zsns3ex.png)

1. `<header>`: used to define the header of a document or section.

```html
<header>
  <h1>My Website</h1>
  <nav>
    <a href="#about">About</a> | <a href="#services">Services</a> |
    <a href="#contact">Contact</a>
  </nav>
</header>
```

2. `<main>`: used to define the main content of a document.

```html
<main>
  <h2>Welcome to my website</h2>
  <p>This is the main content of my website.</p>
</main>
```

3. `<article>`: used to define a self-contained composition in a document.

```html
<article>
  <h3>My Blog Post</h3>
  <p>This is a blog post about HTML.</p>
</article>
```

4. `<section>`: used to define a section in a document.

```html
<section>
  <h3>About Me</h3>
  <p>I am a web developer.</p>
</section>
```

5. `<aside>`: used to define content aside from the main content.

```html
<aside>
  <h4>Related Links</h4>
  <ul>
    <li><a href="#">HTML Tutorials</a></li>
    <li><a href="#">CSS Tutorials</a></li>
    <li><a href="#">JavaScript Tutorials</a></li>
  </ul>
</aside>
```

6. `<footer>`: used to define the footer for a document or section.

```html
<footer>
  <p>Copyright &copy; 2022</p>
</footer>
```

## V. Multimedia elements

Multimedia elements are HTML elements that allow you to embed audio, video, images, and other multimedia content into a web page. These multimedia elements allow you to enrich the content of your web pages and provide a more engaging user experience for your visitors.

1. `<img>`: used to embed an image into a web page.

```html
<img src="image.jpg" alt="An Example Image" />
```

2. `<audio>`: used to embed an audio file into a web page.</audio>

```html
<audio controls>
  <source src="song.mp3" type="audio/mpeg" />
  Your browser does not support the audio element.
</audio>
```

3. `<video>`: used to embed a video file into a web page.

```html
<video controls width="320" height="240">
  <source src="movie.mp4" type="video/mp4" />
  Your browser does not support the video element.
</video>
```

4. `<figure>` and `<figcaption>`: used to embed images and provide a caption for them.

```html
<figure>
  <img src="image.jpg" alt="An Example Image" />
  <figcaption>An example image caption</figcaption>
</figure>
```

5. `<picture >`: used to provide different images for different display conditions.

```html
<picture>
  <source srcset="image-small.jpg" media="(max-width: 767px)" />
  <source srcset="image-large.jpg" media="(min-width: 768px)" />
  <img src="image-small.jpg" alt="An Example Image" />
</picture>
```

## VI. HTML Attributes

HTML attributes are additional values that are added to HTML elements to provide more information or change the default behavior of the elements. These HTML attributes allow you to provide additional information and control the behavior of HTML elements, which helps you create more functional and effective web pages.

1. `class`: used to apply CSS styles to an element.

```html
<p class="highlight">This is an example of using the class attribute.</p>
```

2. `id`: used to apply unique styles to a specific element.

```html
<p id="unique">This is an example of using the id attribute.</p>
```

3. `src`: used to specify the source URL for an `<img>` element.

```html
<img src="image.jpg" alt="An Example Image" />
```

4. `href`: used to specify the target URL for a link created with the `<a>` element.

```html
<a href="https://www.example.com">Visit Example.com</a>
```

5. `width` and `height`: used to specify the dimensions of an `<img>` or `<video>` element.

```html
<img src="image.jpg" alt="An Example Image" width="320" height="240" />
```

6. `alt`: used to provide alternative text for an `<img>` element.

```html
<img src="image.jpg" alt="An Example Image" />
```

7. `target`: used to specify the target window or frame for a link created with the `<a>` element.

```html
<a href="https://www.example.com" target="_blank"
  >Visit Example.com in a new tab</a
>
```

## VII. HTML Forms

HTML forms are used to collect data from users. They allow you to create input fields, checkboxes, radio buttons, drop-down lists, and other elements that let users interact with your web page.

```html
<form action="https://www.example.com/submit-form" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required />

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required />

  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required />

  <input type="submit" value="Submit" />
</form>
```

1. `<form>`: used to define the form and its properties.
   `action`: attribute specifies the URL that the form data will be sent to when it's submitted
   `method`: attribute specifies the HTTP method to be used for sending the form data (in this case, `post`).

2. `<input>`: define the different fields that the user can interact with.
   `type`: attribute specifies the type of field (e.g., text, email, password),
   `id`: attribute is used to associate the input field with a label
   `name`: attribute specifies the name of the form field.

3. `required`: the process of checking the user input data in an HTML form to ensure that it meets certain criteria before it's submitted

## VII. HTML Tables

HTML tables are used to represent tabular data on a web page. They allow you to organize data into rows and columns, making it easier to understand and compare data.

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Email</th>
      <th>Country</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John Doe</td>
      <td>johndoe@example.com</td>
      <td>USA</td>
    </tr>
    <tr>
      <td>Jane Doe</td>
      <td>janedoe@example.com</td>
      <td>Canada</td>
    </tr>
    <tr>
      <td>Jim Smith</td>
      <td>jimsmith@example.com</td>
      <td>Australia</td>
    </tr>
  </tbody>
</table>
```

- `<table>`: used to define the table and its properties
- `<thead>`: contains the header row
- `<tbody>`: contains the data rows
- `<tr>`: represent for each row
- `<td>`: represent for each cell

**Note:** The header row is defined using <th> elements instead of <td> elements, as header cells are typically displayed differently from regular data cells.

## VIII. Web Accessibility

Web accessibility refers to making web content and web applications usable by people with disabilities

1. Use semantic HTML elements: Semantic elements, such as `<header>`, `<nav>`, `<main>`, `<article>`, and `<footer>`, give structure to your web page and provide information about its content to assistive technologies, such as screen readers. Example:

```html
<header>
  <h1>My Web Page</h1>
</header>
<nav>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
<main>
  <h2>Welcome to My Web Page</h2>
  <p>This is the main content of my web page.</p>
</main>
<footer>
  <p>Copyright &copy; 2023 My Company</p>
</footer>
```

2. Use descriptive and meaningful text: Descriptive text, such as alt text for images, can help users understand the content of your web page even if they can't see the images. Example:

```html
<img src="dog.jpg" alt="A picture of a cute dog" />
```

3. Provide captions and transcripts: Captions and transcripts help users who are deaf or hard of hearing understand audio and video content. Example:

```html
<video controls>
  <source src="video.mp4" type="video/mp4" />
  <track src="captions.vtt" kind="captions" srclang="en" label="English" />
</video>
```

4. Make sure your site is keyboard accessible: Keyboard accessibility is important for users who cannot use a mouse, such as those with motor disabilities. Example:

```html
<button type="button">Click Me</button>
```

## IX. Exercises

A portfolio wesbites should include the following elements:

1. Introduction: Start with a brief introduction that gives an overview of who you are, what you do, and what you hope to achieve with your portfolio.
2. About me: Include a section that provides a more detailed introduction to yourself, including your background, education, experience, and skills.
3. Work samples: Highlight your best work by showcasing a variety of projects, both past and present. Make sure to include images and descriptions that demonstrate your skills and expertise.
4. Skills: List your technical and creative skills, and highlight the ones you specialize in. This can include programming languages, design software, and other relevant tools.
5. Accomplishments: Share any relevant accomplishments, such as awards, publications, or speaking engagements.
6. Testimonials: Include testimonials from clients or coworkers who can speak to your skills and professionalism.
7. Contact information: Provide a clear and easy-to-find way for people to get in touch with you, including your email, phone number, and any social media profiles you would like to link to.
8. Call to action: End your portfolio with a clear call to action, such as a request for a job or freelance opportunity.
