# 20-11-10 CSS Grid Primary

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode

### Linking files
1. create an HTML file called `index.html`
1. create a css file called `style.css`
2. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
3. check that the file is linked by setting the `background-color` property of the body to any color other than white/gray and open the HTML file using `ctrl o` in the browser

### Assignment
Create a simplified dupe of a Github user page based on [this](https://github.com/Kevin-CodeCrew) profile using the wireframe image provided. Use CSS grid to layout the HTML elements.

### Content
1. create a navigation element with four links mimicking the wireframe that open in the same tab
1. render the text `Popular Repositories` in large bold font below the navigation element
1. render a profile image, username, user's full name, user's job title, an two buttons with the text `Follow User` and `More Options` mimicking the wireframe
1. render four elements with a project name, and description mimicking the wireframe - the project name should link to your corresponding repository and open in a new tab

### Styling
1. style the navigation element with a gray background mimicking the wireframe
1. style links in the navigation element with white text, space between each, and without the underline `hint : text-decoration` mimicking the wireframe
1. style the buttons with space between the content and border, a green background, and rounded edges `hint : border-radius`
1. style each project section with a gray border rounded border and space between the content and the border mimicking the wireframe

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/htmlCSS.md)

[MDN Resource](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)
