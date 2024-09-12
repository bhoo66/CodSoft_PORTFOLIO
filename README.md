Creating a personal portfolio is a fantastic way to showcase your skills, experience, and projects as a beginner web developer. Below is a guide to help you build a basic portfolio using HTML and CSS, including a sample code template for each section. 

### **1. Project Structure**

Create a folder for your project, for example, `personal-portfolio`. Inside this folder, you should have:

- `index.html` (for HTML structure)
- `styles.css` (for CSS styling)

### **2. HTML Structure**

Here’s a basic HTML template for your portfolio:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>My Name</h1>
            <p>Web Developer | Designer | Creator</p>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <img src="your-photo.jpg" alt="Your Photo">
            <h2>About Me</h2>
            <p>Hello! I'm a web developer with a passion for creating beautiful and functional websites. With experience in HTML, CSS, and JavaScript, I build user-friendly and responsive designs.</p>
        </div>
    </section>

    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>Responsive Design</li>
                <li>Graphic Design</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <img src="project1.jpg" alt="Project 1">
                <h3>Project 1</h3>
                <p>A brief description of Project 1. Explain what technologies were used and the goals of the project.</p>
            </div>
            <div class="project">
                <img src="project2.jpg" alt="Project 2">
                <h3>Project 2</h3>
                <p>A brief description of Project 2. Explain what technologies were used and the goals of the project.</p>
            </div>
        </div>
    </section>

    <section id="resume">
        <div class="container">
            <h2>Resume</h2>
            <p>Download my <a href="resume.pdf" download>resume</a> to learn more about my experience and skills.</p>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
            <p>Phone: +1 (555) 123-4567</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 My Name. All rights reserved.</p>
            <p>Follow me on <a href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn</a></p>
        </div>
    </footer>
</body>
</html>
```

### **3. CSS Styling**

Here’s a basic CSS template to style your portfolio. Save this in `styles.css`:

```css
/* Reset some default styles */
body, h1, h2, h3, p, ul {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Basic styling for the body */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

/* Container to center and constrain content */
.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

/* Header styling */
header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin-bottom: 10px;
}

header p {
    margin-top: 0;
    font-style: italic;
}

/* About section styling */
#about {
    padding: 20px 0;
    text-align: center;
}

#about img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 10px;
}

/* Skills section styling */
#skills {
    background: #fff;
    padding: 20px 0;
}

#skills ul {
    list-style: none;
    padding: 0;
}

#skills ul li {
    background: #ddd;
    margin: 5px 0;
    padding: 10px;
}

/* Projects section styling */
#projects {
    padding: 20px 0;
}

.project {
    margin-bottom: 20px;
}

.project img {
    width: 100%;
    height: auto;
}

.project h3 {
    margin-top: 10px;
}

/* Resume section styling */
#resume {
    background: #fff;
    padding: 20px 0;
}

/* Contact section styling */
#contact {
    padding: 20px 0;
    text-align: center;
}

/* Footer styling */
footer {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

footer p {
    margin: 5px 0;
}

footer a {
    color: #fff;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
```

### **4. Customization Tips**

- **Images**: Replace placeholder image URLs (e.g., `your-photo.jpg`, `project1.jpg`) with actual images of yourself and your projects.
- **Content**: Update text content to accurately reflect your personal bio, skills, projects, and contact information.
- **Responsive Design**: Consider adding media queries in your CSS to make your portfolio responsive on different devices.

### **5. Testing and Deployment**

- **Test Locally**: Open `index.html` in a web browser to see how it looks and make adjustments as needed.
- **Deploy Online**: Consider using platforms like GitHub Pages, Netlify, or Vercel for free hosting of your portfolio.

By following this guide, you can create a visually appealing and functional personal portfolio to showcase your skills and projects effectively.
