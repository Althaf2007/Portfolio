# Ex01 Portfolio
## Date: 25-04-2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

portt.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <link rel="stylesheet" href="porttt.css">
</head>
<body>

  <header>
    <h1 class="logo">K.Mohamed Althaf</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#tech">Tech Stack</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-image">
      <img src="my pic.jpg" alt="Profile">
    </div>

    <h2>Hey there, I'm <span>K.Mohamed Althaf</span></h2>
    <p>Designer | Full Stack Developer</p>
    <p class="tagline">I develop a fulfiiling web experience</p>
  </section>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>
      I am a 2nd year engineering student pursuing Artificial Intelligence and Machine Learning.
      I am an aspiring full-stack developer passionate about building scalable and user-friendly applications.
    </p>
  </section>

  <section id="skills" class="section light">
    <h2>Core Skills</h2>

    <div class="skill-box">
      <h3>Design</h3>
      <div class="skills">
        <span>UI/UX</span>
        <span>Canva</span>
        <span>Figma</span>
      </div>
    </div>

    <div class="skill-box">
      <h3>Frontend</h3>
      <div class="skills">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>React</span>
      </div>
    </div>

    <div class="skill-box">
      <h3>Backend</h3>
      <div class="skills">
        <span>Node.js</span>
        <span>Express</span>
        <span>API</span>
      </div>
    </div>
  </section>

  <section id="tech" class="section">
    <h2>Tech Stack</h2>
    <div class="stack">
      <span>MongoDB</span>
      <span>GitHub</span>
      <span>SQL</span>
      <span>Cloud</span>
    </div>
  </section>

  <section id="contact" class="section light">
    <h2>Contact</h2>
    <p>Email: mohamed.althaf2707@gmail.com</p>
    <p>Location: Chennai</p>
  </section>

  <footer>
    <p>© 2026 K.Mohamed Althaf</p>
  </footer>

</body>
</html>
```

porttt.css
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", sans-serif;
}

body {
  background: #1d0743;
  color: white;
}

header {
  display: flex;
  justify-content: space-between;
  padding: 20px 10%;
  background: #020332;
}

nav a {
  margin-left: 20px;
  color: white;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 80px 20px;
}

.hero img {
  width: 200px;
  height: 200px;
  border-radius: 20px;
}

.hero h2 {
  font-size: 2.5rem;
  margin-top: 20px;
}

.hero span {
  color: #6798d0;
}

.section {
  padding: 60px 10%;
  text-align: center;
}

.light {
  background: #020332;
}

.skills, .stack {
  display: flex;
  justify-content: center;
  gap: 10px;
  flex-wrap: wrap;
}

.skills span, .stack span {
  background: #1f1f1f;
  padding: 8px 15px;
  border-radius: 20px;
}

footer {
  text-align: center;
  padding: 20px;
}
```
## OUTPUT

<img width="1884" height="1027" alt="image" src="https://github.com/user-attachments/assets/440850a3-d3f9-4e36-98d9-050532bf0d92" />
<img width="1875" height="977" alt="image" src="https://github.com/user-attachments/assets/d400cb97-0685-42c7-b221-513868672e56" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
