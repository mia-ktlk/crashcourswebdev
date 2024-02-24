
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

### Lesson 1: HTML Boilerplate

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

