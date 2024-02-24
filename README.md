
# Mia X The SteamBoat
## Workshop Outline: Introduction to Web Development
### Total Duration: 1 Hour and 30 Minutes

**Survey:** If you have not taken this survey yet please do: [Survey Link](https://forms.gle/RxA7BoVPGxNffY2R6)

## Part 1: Diving into HTML/CSS and JavaScript (45 minutes)
**Objective:** Introduce participants to the building blocks of web development through a hands-on project of building a Wikipedia page. Participants will learn the fundamentals of HTML and CSS, and get a small taste of JavaScript. The goal is for everyone to understand how these elements work together to create websites.

**Details:**
- **HTML Basics** (15 minutes): Introduction to HTML structure (elements, tags, attributes), creating a simple page (headings, paragraphs, links, images).
- **CSS 101** (15 minutes): Basics of CSS (selectors, properties, values), styling our HTML page, introducing the box model, and playing with colors and fonts.
- **Jumping into JavaScript** (15 minutes): Brief intro to JavaScript, variables, functions, and DOM manipulation. Participants will add a simple interactive feature to their Wikipedia page (e.g., a button that changes text).

## Part 2: Bootstrap Magic (20 minutes)
**Objective:** Introduce Bootstrap as a powerful tool to make web development faster and easier. Participants will learn how to use Bootstrap's grid system and components to design responsive websites.

**Details:**
- **Introduction to Bootstrap** (5 minutes): What is Bootstrap and why use it? Overview of Bootstrap's grid system and responsive design principles.
- **Using Bootstrap Components** (15 minutes): Hands-on with Bootstrap components (navigation bars, cards, forms). Quick exercise to integrate some Bootstrap components into the previously created Wikipedia page.

## Part 3: Git Going with Git and GitHub (10 minutes)
**Objective:** Familiarize participants with Git for version control and GitHub for code sharing. Teach the basics of cloning a repository with a Bootstrap template for a website to showcase an app.

**Details:**
- **Git Basics** (5 minutes): Introduction to version control, why Git is awesome, basic Git commands (init, add, commit, push).
- **Cloning with GitHub** (5 minutes): Creating a GitHub account (if needed), cloning a Bootstrap app template repository to local machine for the next exercise.

## Part 4: Editing and Deploying the App Template (15 minutes)
**Objective:** Apply what we’ve learned by editing the Bootstrap template and deploying it using GitHub Pages. This section aims to empower participants with the ability to make a website showcasing the details of the app or product they end up making for their hackathon.

**Details:**
- **Customizing the App Template** (10 minutes): Quick walkthrough on how to modify the cloned Bootstrap template (changing text, images, and adding a new section).
- **Deploying the App** (5 minutes): Introduction to deployment options (GitHub Pages), deploying the customized app so participants can share their work with the world.

## Wrap-Up and Q&A
**Objective:** Conclude the workshop with a summary of what was covered. Open the floor for any questions, encouraging participants to share their thoughts and seek clarification on any concepts.


---

### Getting Started

Let's make sure you have the necessary tools and resources to get started.

#### Step 1: Take the Survey

Please take a moment to fill out this survey to help me understand your current skill level and goals for this workshop: [Survey Link](https://forms.gle/RxA7BoVPGxNffY2R6).

#### Step 2: Download Visual Studio Code (VSCode)

Download Visual Studio Code (VSCode) from the official website: [Download VSCode](https://code.visualstudio.com/).
If you prefer to use another Integrated Development Environment (IDE) for web development, feel free to use whichever tool you're comfortable with. Just make sure it supports HTML, CSS, and JavaScript development.

#### Step 3: Install Extensions (Optional)

If you're using Visual Studio Code, I recommend installing the "Live Server" extension by Ritwick Dey. This extension allows you to launch a local development server with live reload capability, making it easier to preview your web pages as you code.

To install the "Live Server" extension:
1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the square icon in the sidebar or pressing `Ctrl+Shift+X`.
3. Search for "Live Server" in the extensions marketplace.
4. Click on the "Install" button next to the "Live Server" extension.

---

### Lesson 1: Terminal/Command Line

#### What is the Terminal/Command Line?

The terminal, also known as the command line or shell, is a text-based interface for interacting with your computer's operating system. It allows you to execute commands to perform various tasks such as navigating through directories, managing files, and running programs.

#### Windows Instructions:

1. **Open Command Prompt**:
   - Press `Windows + R` to open the Run dialog.
   - Type `cmd` and press Enter.

2. **Navigate to a Directory**:
   - Use the `cd` command followed by the path of the directory you want to navigate to.
     ```
     cd path\to\directory
     ```

3. **Create a New Directory**:
   - Use the `mkdir` command followed by the name of the new directory.
     ```
     mkdir new_directory
     ```

4. **Create a File**:
   - Use the `type nul >` command followed by the name of the file you want to create.
     ```
     type nul > wiki.html
     ```

#### Mac Instructions:

1. **Open Terminal**:
   - Press `Command + Space` to open Spotlight Search.
   - Type `Terminal` and press Enter.

2. **Navigate to a Directory**:
   - Use the `cd` command followed by the path of the directory you want to navigate to.
     ```
     cd /path/to/directory
     ```

3. **Create a New Directory**:
   - Use the `mkdir` command followed by the name of the new directory.
     ```
     mkdir new_directory
     ```

4. **Create a File**:
   - Use the `touch` command followed by the name of the file you want to create.
     ```
     touch wiki.html
     ```

These commands will help you navigate through directories, create new directories, and create files in the terminal/command line interface on both Windows and Mac operating systems.


### Recommendation: GitBash for Windows Users

If you're using Windows and prefer a Unix-like command line experience, I highly recommend using GitBash. GitBash provides a lightweight and powerful terminal emulator that includes Git for version control along with a Unix-like command line experience.

#### Why GitBash?

1. **Unix-Like Environment**: GitBash provides a Unix-like command line interface, which is more familiar to me as a developer accustomed to working with Linux or macOS.

2. **Git Integration**: GitBash comes bundled with Git, allowing me to perform version control tasks directly from the command line without needing to install additional software.

3. **Enhanced Productivity**: With GitBash, I can leverage powerful Unix commands and scripting capabilities to streamline my development workflow and automate repetitive tasks.

4. **Compatibility**: GitBash ensures compatibility with many Unix-based development tools and utilities, making it easier for me to collaborate with teams using different operating systems.

#### How to Install GitBash:

1. **Download Git for Windows**: I can visit the official Git website and download the Git for Windows installer: [Git for Windows](https://gitforwindows.org/)

2. **Run the Installer**: After downloading the installer, I can double-click the file and follow the on-screen instructions to install GitBash on my system.

3. **Launch GitBash**: Once installed, I can launch GitBash from the Start menu or by searching for "Git Bash" in the Windows search bar.

4. **Customize Settings (Optional)**: I have the option to customize GitBash settings such as font size, color scheme, and default shell preferences to suit my preferences.

By using GitBash, I'll have access to a powerful and versatile command line environment tailored for web development on the Windows platform.


---

### Lesson 2: HTML Boilerplate

1. Open the wiki.html file you created using vsCode

2. Write the boilerplate code for an html file

**For Further Reading:** [Introduction to HTML - W3Schools](https://www.w3schools.com/html/html_intro.asp)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>
   

</body>
</html>
```

Explanation:

1. `<!DOCTYPE html>`: 
   - This is a document type declaration that tells the browser which version of HTML the page is written in. In this case, it's HTML5, which is the latest version of HTML.

2. `<html lang="en">`:
   - This tag marks the beginning of the HTML document and indicates that the language of the document is English (`lang="en"`). It encloses all the content of the HTML document.

3. `<head>`:
   - The `<head>` element contains meta-information about the HTML document, such as character encoding, viewport settings, stylesheets, scripts, and the document's title. This section is not displayed on the web page itself.

4. `<meta charset="UTF-8">`:
   - This meta tag specifies the character encoding for the document. UTF-8 is a widely-used character encoding that supports a wide range of characters from various languages.

5. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`:
   - This meta tag configures the viewport settings for the page, especially for responsive web design. It ensures that the width of the viewport matches the device's width and sets the initial zoom level to 1.0, which is equivalent to 100%.

6. `<title></title>`:
   - The `<title>` element defines the title of the HTML document, which appears in the browser's title bar or tab. It's also used by search engines and social media platforms when displaying search results or shared links.

7. `<body>`:
   - The `<body>` element contains all the content that is visible on the web page, including text, images, links, videos, and other HTML elements. This is where the actual content of the web page resides.

8. `</body>` and `</html>`:
   - These are closing tags that mark the end of the `<body>` and `<html>` elements, respectively. All HTML content must be enclosed within these tags.

Overall, this HTML boilerplate provides the basic structure and meta-information for an HTML document, ensuring proper rendering and functionality across different devices and browsers.

--- 

### Lesson 3: Explaining HTML Tags

**For Further Reading:** [Introduction to HTML - W3Schools](https://www.w3schools.com/html/html_basic.asp)

This example HTML document demonstrates various HTML tags and their functions:

```html
<!DOCTYPE html> <!-- This declares the document type and specifies that the document is an HTML5 document. -->

<html lang="en"> <!-- This marks the beginning of the HTML document and specifies the language as English. -->

<head>
    <meta charset="UTF-8"> <!-- This meta tag specifies the character encoding for the document, which is UTF-8. -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- This meta tag sets the viewport properties for responsive design. -->
    <title>Example Wikipedia Page</title> <!-- This tag defines the title of the HTML document, which appears in the browser's title bar or tab. -->
</head>

<body>
    <header>
        <h1>Wikipedia</h1> <!-- This tag represents the main heading of the document, typically the title of the page. -->
    </header>

    <h2>Cats</h2> <!-- This tag represents a level 2 heading, providing a subheading for the content that follows. -->

    <p>Cats (Felis catus), commonly referred to as domestic <a href="https://en.wikipedia.org/wiki/Cat">cats</a>, are small carnivorous mammals that belong to the family Felidae. As one of the most popular pets worldwide, cats have a long history of companionship with humans, dating back thousands of years. Renowned for their independent nature and keen hunting instincts, cats are valued for their ability to control pests such as rodents in human habitats. Domestic cats exhibit a diverse range of breeds, each with unique physical characteristics and temperament traits. From the elegant Siamese to the majestic Maine Coon, these breeds reflect centuries of selective breeding by humans. While domestic cats primarily live in homes as beloved companions, feral populations can also be found thriving in urban and rural environments across the globe. With their enigmatic personalities and captivating charm, cats continue to capture the hearts of people worldwide, earning their place as one of humanity's most cherished animal companions.</p>
</body>
</html>
```

Explanation:

- `<title>Example Wikipedia Page</title>`: Defines the title of the HTML document.
- `<body>`: Contains all the visible content of the web page.
- `<header>`: Represents a header section of the document.
- `<h1>Wikipedia</h1>`: Represents the main heading of the document.
- `<h2>Cats</h2>`: Represents a level 2 heading, providing a subheading for the content that follows.
- `<p>`: Represents a paragraph of text.
- `<a href="https://en.wikipedia.org/wiki/Cat">cats</a>`: Represents a hyperlink, linking to the Wikipedia page about cats.

---
### Lesson 4: Exploring HTML Elements and Attributes



```html
<!DOCTYPE html> <!-- This declares the document type and specifies that the document is an HTML5 document. -->
<html lang="en"> <!-- This marks the beginning of the HTML document and specifies the language as English. -->
<head>
    <meta charset="UTF-8"> <!-- This meta tag specifies the character encoding for the document, which is UTF-8. -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- This meta tag sets the viewport properties for responsive design. -->
    <title>Example Wikipedia Page</title> <!-- This tag defines the title of the HTML document, which appears in the browser's title bar or tab. -->
</head>
<body>
    <header>
        <h1>Wikipedia</h1> <!-- This tag represents the main heading of the document, typically the title of the page. -->
    </header>

    <section id ="intro"> <!-- This tag represents a section of content in the document, with the "intro" ID attribute assigned for styling or scripting purposes. -->
        <h2>Cats</h2> <!-- This tag represents a level 2 heading, providing a subheading for the content that follows. -->
        <p>Cats (Felis catus), commonly referred to as domestic <a href="https://en.wikipedia.org/wiki/Cat">cats</a>, are small carnivorous mammals that belong to the family Felidae. As one of the most popular pets worldwide, cats have a long history of companionship with humans, dating back thousands of years. Renowned for their independent nature and keen hunting instincts, cats are valued for their ability to control pests such as rodents in human habitats. Domestic cats exhibit a diverse range of breeds, each with unique physical characteristics and temperament traits. From the elegant Siamese to the majestic Maine Coon, these breeds reflect centuries of selective breeding by humans. While domestic cats primarily live in homes as beloved companions, feral populations can also be found thriving in urban and rural environments across the globe. With their enigmatic personalities and captivating charm, cats continue to capture the hearts of people worldwide, earning their place as one of humanity's most cherished animal companions.</p>
    </section>


    <section id="text"> <!-- Another section with an ID attribute assigned. -->
        <h2>Text Formatting</h2> <!-- Another heading within this section. -->
        <p>This is a paragraph demonstrating text formatting in HTML. You can use <strong>strong</strong>, <em>emphasized</em>, <u>underlined</u>, and <del>deleted</del> text.</p> <!-- This paragraph demonstrates various text formatting elements such as strong, emphasized, underlined, and deleted text. -->
        <p>You can also use <sup>superscript</sup> and <sub>subscript</sub> text.</p> <!-- This paragraph demonstrates superscript and subscript text. -->
        <p>Inline code: <code>&lt;code&gt;</code></p> <!-- This paragraph demonstrates inline code formatting. -->
        <p>Blockquote:</p>
        <blockquote> <!-- This tag represents a blockquote, used for quoting text from another source. -->
            "This is a blockquote."
        </blockquote>
    </section>


    <section id="lists"> <!-- Another section with an ID attribute assigned. -->
        <h2>Types of Cat</h2> <!-- Another heading within this section. -->
        <h3>Ordered List</h3> <!-- Subheading for an ordered list. -->
        <ol> <!-- This tag represents an ordered list. -->
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ol>
        <h3>Unordered List</h3> <!-- Subheading for an unordered list. -->
        <ul> <!-- This tag represents an unordered list. -->
            <li>Item A</li>
            <li>Item B</li>
            <li>Item C</li>
        </ul>
    </section>

    <section id="images"> <!-- Another section with an ID attribute assigned. -->
        <h2>Cat Image</h2> <!-- Another heading within this section. -->
        <img src="https://cdn.britannica.com/34/235834-050-C5843610/two-different-breeds-of-cats-side-by-side-outdoors-in-the-garden.jpg?w=400&h=300&c=crop" alt="Placeholder Image"> <!-- This tag represents an image, with the "src" attribute specifying the image URL and the "alt" attribute providing alternative text for accessibility. -->
    </section>

</body>
</html>
```

The HTML `id` attribute is used to specify a unique identifier for an HTML element.

You cannot have more than one element with the same id in an HTML document.

### Using The id Attribute

The `id` attribute specifies a unique identifier for an HTML element. The value of the id attribute must be unique within the HTML document.

The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.

The syntax for id is: write a hash character (#), followed by an id name. Then, define the CSS properties within curly braces {}.

In the following example, we have an `<h1>` element that points to the id name "myHeader". This `<h1>` element will be styled according to the `#myHeader` style definition in the head section:

For further reading, visit [HTML id Attribute - W3Schools](https://www.w3schools.com/html/html_id.asp).

Explanation:
<section>: The section tag defines a section in a document, which can be used to group related content together. It's often used to divide a page into thematic sections. The id attribute provides a unique identifier for each section, allowing for easy navigation or styling.
<ol>: The ol tag defines an ordered (numbered) list, while <ul> defines an unordered (bulleted) list. Within these tags, <li> represents each individual list item.
<img>: The img tag embeds an image in the document. The src attribute specifies the image URL, and the alt attribute provides alternative text for accessibility.

---

### Lesson 5: Tables, Forms, and Navs

In this lesson, we explore how to use tables, forms, and navigation elements in HTML.

#### Tables

Tables are used to display data in rows and columns. They consist of `<table>` elements, with rows defined by `<tr>` elements and cells defined by `<td>` or `<th>` elements.

```html
<section id="tables">
    <h2>Tables</h2>
    <table>
        <thead>
            <tr>
                <th>Header 1</th>
                <th>Header 2</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Row 1, Cell 1</td>
                <td>Row 1, Cell 2</td>
            </tr>
            <tr>
                <td>Row 2, Cell 1</td>
                <td>Row 2, Cell 2</td>
            </tr>
        </tbody>
    </table>
</section>
```

#### Forms

Forms are used to collect user input. They consist of `<form>` elements, with input fields defined by `<input>`, `<textarea>`, and `<select>` elements.

```html
<section id="forms">
    <h2>Forms</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
        <input type="submit" value="Submit">
    </form>
</section>
```

#### Navs

The `<nav>` tag is used to define navigation links. It typically contains an unordered list (`<ul>`) of links (`<a>` tags).

```html
<header>
    <h1>Wikipedia</h1>
    <nav>
        <ul>
            <li><a href="#intro">Intro</a></li>
            <li><a href="#text">Text</a></li>
            <li><a href="#lists">Lists</a></li>
            <li><a href="#images">Images</a></li>
            <li><a href="#tables">Tables</a></li>
            <li><a href="#forms">Forms</a></li>
        </ul>
    </nav>
</header>
```

#### Further Reading

- [HTML Table Tutorial - W3Schools](https://www.w3schools.com/html/html_tables.asp)
- [HTML Forms Tutorial - W3Schools](https://www.w3schools.com/html/html_forms.asp)


---


### Lesson 6: Introducing CSS

CSS, or Cascading Style Sheets, is a style sheet language used for describing the presentation of a document written in HTML. It allows you to control the layout, colors, fonts, and other visual aspects of your web pages. In this lesson, we'll explore some basic CSS concepts and how to apply them to our HTML document.

#### Example Code Explanation:

```css
/* Resetting default margin and padding */
body, h1, h2, h3, p, ul, ol, li, table, th, td, form, label, input, textarea {
    margin: 0;
    padding: 0;
}

/* Setting body font and background color */
body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    padding: 20px;
}

/* Header styles */
header {
    background-color: #ffffff;
    padding: 20px;
    border-bottom: 2px solid #e6e6e6;
}

h1 {
    color: #1a1a1a;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    text-decoration: none;
    color: #555555;
}

nav ul li a:hover {
    color: #000000;
}

/* Section styles */
section {
    background-color: #ffffff;
    margin-bottom: 20px;
    padding: 20px;
    border: 1px solid #e6e6e6;
}

h2 {
    color: #1a1a1a;
    margin-bottom: 10px;
}

p {
    color: #333333;
    margin-bottom: 15px;
}

blockquote {
    color: #666666;
    font-style: italic;
}

/* Image styles */
img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
    border: 1px solid #cccccc;
    margin-bottom: 20px;
}

/* Table styles */
table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
}

th, td {
    border: 1px solid #cccccc;
    padding: 8px;
    text-align: left;
}

th {
    background-color: #f2f2f2;
}

/* Form styles */
form {
    margin-bottom: 20px;
}

label {
    display: block;
    margin-bottom: 5px;
    color: #333333;
}

input[type="text"],
input[type="email"],
textarea {
    width: 100%;
    padding: 8px;
    margin-bottom: 10px;
    border: 1px solid #cccccc;
    border-radius: 4px;
}

input[type="submit"] {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

input[type="submit"]:hover {
    background-color: #45a049;
}

.pb-3 {
    padding-bottom: 7px;
}
```

#### Explanation:

- The `footer` tag: This tag represents a footer for a document or section. It typically contains information about the author, copyright, contact information, or links to related documents.
  
- CSS (Cascading Style Sheets): CSS is a style sheet language used to style HTML documents. It allows you to define styles for various elements such as fonts, colors, layouts, and more. CSS rules consist of a selector (which selects the HTML element) and a declaration block (which contains the style properties and values).

To use CSS, you can either include it directly within an HTML document using `<style>` tags in the `<head>` section, or link an external CSS file using the `<link>` tag. The latter method is preferred for larger projects as it promotes code organization and reusability.

In the provided example, we've linked an external CSS file (`style.css`) to our HTML document using the `<link>` tag in the `<head>` section:

```html
<link rel="stylesheet" href="style.css">
```

This allows us to define and apply styles to various elements in our HTML document, resulting in a visually appealing and well-structured web page.


---

### Lesson 7: JavaScript Example

#### Creating a New JavaScript File:

##### Windows:

1. Open Command Prompt.
2. Navigate to the directory where you want to create the file using the `cd` command.
3. Type `type nul > moving.js` and press Enter.

##### macOS:

1. Open Terminal.
2. Navigate to the directory where you want to create the file using the `cd` command.
3. Type `touch moving.js` and press Enter.

#### JavaScript Example (moving.js):

```javascript
window.onload = function() {
    var header = document.querySelector('.pb-3');
    var moveInterval = setInterval(moveTitle, 2000); // Move every 2 seconds
    var distance = 50; // Distance to move

    function moveTitle() {
        header.style.position = 'relative';
        header.style.animation = 'moveTitle 2s infinite';
    }
}
```

1. **`window.onload = function() { ... }`**:
   - This is an event handler that runs the code inside the function when the window (the browser window) has finished loading.
   - It ensures that the JavaScript code runs after all the HTML content has been loaded.

2. **`var header = document.querySelector('.pb-3');`**:
   - `document.querySelector('.pb-3')` selects the first element in the document with the class `pb-3`.
   - The selected element is stored in the variable `header` for later use.

3. **`var moveInterval = setInterval(moveTitle, 2000);`**:
   - `setInterval()` is a JavaScript function that repeatedly calls a function (`moveTitle` in this case) at a specified time interval (2000 milliseconds, or 2 seconds).
   - It returns a numeric ID (`moveInterval`) that can be used to later stop the interval using `clearInterval()`.

4. **`var distance = 50;`**:
   - This line declares a variable named `distance` and assigns it the value of `50`.
   - However, this variable is not used in the provided code snippet.

5. **`function moveTitle() { ... }`**:
   - This declares a JavaScript function named `moveTitle`.
   - Inside this function, we define the behavior of moving the title.

6. **`header.style.position = 'relative';`**:
   - This line sets the CSS `position` property of the `header` element to `relative`.
   - It means that the element will be positioned relative to its normal position.

7. **`header.style.animation = 'moveTitle 2s infinite';`**:
   - This line applies an animation to the `header` element.
   - The animation is defined in CSS and is called `moveTitle`.
   - It lasts for 2 seconds (`2s`) and repeats indefinitely (`infinite`).


#### Linking JavaScript File in HTML:

To link the JavaScript file in HTML, add the following line within the `<head>` section of your HTML file:

```html
<script src="moving.js"></script>
```

This line tells the browser to load and execute the JavaScript code from the `moving.js` file.

#### Adding Animation in CSS (style.css):

```css
@keyframes moveTitle {
    0% { left: 0; }
    50% { left: 50%; }
    100% { left: 0; }
}
```

Explanation: 
- `@keyframes` is a CSS rule that defines the behavior of an animation.
- `moveTitle` is the name of the animation.
- `0%`, `50%`, and `100%` define the keyframes of the animation.
- `left: 0` means that the element starts at the leftmost position.
- `left: 50%` means that the element moves to the center.
- `infinite` specifies that the animation should repeat indefinitely.

Including this CSS code allows the JavaScript animation to function properly by defining the animation behavior.

---

### Lesson 8: Bootstrap

Bootstrap is a popular front-end framework used for building responsive and mobile-first websites and web applications. It provides a collection of pre-designed components, such as buttons, forms, navigation bars, and more, along with a grid system that helps in creating responsive layouts.

#### Introduction to Bootstrap:

Bootstrap simplifies the process of web development by offering ready-to-use components and styles, which can be easily customized to suit your project needs. It ensures consistency and efficiency in design, making it a preferred choice for developers of all levels.

#### Column and Row System:

One of the key features of Bootstrap is its grid system, which is based on a 12-column layout. Developers can divide the available space into rows and columns, allowing for flexible and responsive design layouts. Columns can be nested within rows, and the grid system automatically adjusts based on the screen size, ensuring that the content looks good on all devices.

To get hands-on experience with Bootstrap's grid system, you can visit [Layoutit](https://www.layoutit.com/build), a web-based interface that allows you to visually design Bootstrap layouts by dragging and dropping components onto a grid.

#### Exploring Bootstrap Themes:

Bootstrap offers a wide range of themes and templates. These themes include pre-designed layouts, styles, and components, saving you time and effort in the design process. You can find a variety of Bootstrap themes on [Start Bootstrap](https://startbootstrap.com/?showAngular=false&showVue=false&showPro=false). Look through the available themes, and once you find one that you like.  [This one](https://startbootstrap.com/theme/new-age) is good if you are making an app


### Instructions:

#### If You Have GitHub Set Up:

1. Go to [Start Bootstrap - New Age Theme](https://startbootstrap.com/theme/new-age).

2. Click on "View Source Code" to access the GitHub repository.

3. On the GitHub repository page, click on the "Code" button.

4. Select "Open with GitHub Desktop" or "Download ZIP" to clone or download the repository to your local machine.

5. If using GitHub Desktop, follow the prompts to clone the repository to your desired location.

6. If downloading the ZIP file, extract its contents to a location on your computer.

7. You now have the files available locally for editing.

#### If You Don't Have GitHub:

1. Go to [Start Bootstrap - New Age Theme](https://startbootstrap.com/theme/new-age).

2. Click on "Download" to download the theme files as a ZIP archive.

3. Extract the downloaded ZIP file to a location on your computer.

4. You now have the theme files available locally for editing.



