# Ex01 Portfolio
## Name: GOKUL SHARAN R
## Reg No: 212223040052
## Date: 13.8.2025

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

## PROGRAM:

## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section"><br><br>
    <h1>Welcome to My Portfolio</h1>
    <h1>SHYAM SUJIN U</h1>
    <h3>B.E. CSE, 3rd Year</h3><br>
    <img src="pic.jpg" alt="My Photo" style="width: 160px;" class="profile-photo"><br><br><br>
    <h4>
      <p>
        I am Shyam Sujin U, a Third-year Computer Science and Engineering student pursuing a B.E degree. I am passionate about web development and have a keen interest in machine learning. I enjoy building innovative projects and enhancing my skills in technology.
      </p>
    </h4>
  </section>

  <section id="about" class="section"><br><br>
    <h2>About Me</h2><br>
    <p>I am a Computer Science and Engineering student passionate about web development and machine learning.</p>
    <p>I specialize in building responsive and interactive web applications using modern frameworks like React.js and Node.js.</p>
    <p>My interests include full-stack development, AI integration in web apps, and developing user-centric designs.</p>
    <p>Currently, I am working on a Cancer Detection System using machine learning as part of my academic project.</p>
    <p>I also actively participate in coding competitions and contribute to open-source projects to enhance my coding skills.</p>
    <p>My goal is to become a proficient full-stack developer and leverage technology to solve real-world problems.</p>
  </section>

  <section id="education" class="section"><br><br>
    <h2>Education</h2>
    <center>
      <table>
        <tr>
          <th>Batch</th>
          <th>Institution</th>
          <th>Course</th>
          <th>Percentage</th>
        </tr>
        <tr>
          <td>2023-2027</td>
          <td>Saveetha Engineering College</td>
          <td>BE Computer Science and Engineering</td>
          <td>85%</td>
        </tr>
        <tr>
          <td>2020-2022</td>
          <td>St.Assisi Matric Higher Secondary School</td>
          <td>11th, 12th - Higher Secondary Education</td>
          <td>90%</td>
        </tr>
        <tr>
          <td>2019-2020</td>
          <td>St.Assisi Matric Higher Secondary School</td>
          <td>10th</td>
          <td>100%</td>
        </tr>
      </table>
    </center>
  </section>

  <section id="skills" class="section"><br><br>
    <h2>Skills</h2><br>
    <h2>Technical Skills</h2><br>
    <h4>I) Programming: C, Java, Python, SQL</h4>
    <h4>II) Web Development: HTML, CSS, JavaScript</h4>
    <h4>III) Machine Learning: Data Science, Algorithms</h4><br>
    
    <h2>Soft Skills</h2><br>
    <h4>I) Communication</h4>
    <h4>II) Project management</h4>
    <h4>III) Problem-Solving</h4>
  </section>

  <section id="contact" class="section"><br><br>
    <h2>Contact Me</h2><br><br>
    <p>Email: shyamsujin4@gmail.com</p>
    <p>LinkedIn: <a href="#">https://www.linkedin.com/in/shyamsujin-u-08615b327/</a></p>
    <p>GitHub: <a href="#">https://github.com/Shyamsujin</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Shyam Sujin U. All rights reserved.</p>
  </footer>
</body>
</html>
```
## CSS
```
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  scroll-behavior: smooth;
}

table {
  width: 70%;
  margin: auto;
  border-collapse: collapse;
}

th, td {
  border: 1px solid black;
  padding: 10px;
  text-align: center;
}

th {
  background-color: #f2f2f2;
}

nav {
  background-color: #333;
  padding: 10px 0;
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 100;
}

nav ul {
  list-style-type: none;
  text-align: center;
}

nav ul li {
  display: inline;
  margin: 0 20px;
}

nav a {
  text-decoration: none;
  color: white;
  font-weight: bold;
}

nav a:hover {
  color: #00bcd4;
}

.section {
  padding: 50px 20px;
  min-height: 100vh;
  text-align: center;
}

#home {
  background-color: rgb(107, 222, 208);
}

#about {
  background-color: #e6f7ff;
}

#education {
  background-color: #d9f7be;
}

#skills {
  background-color: #d9f7be;
}

#projects {
  background-color: #fff1b8;
}

#contact {
  background-color: #ffe7ba;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px 0;
}

.profile-photo {
  width: 140px;
  height: 170px;
  border-radius: 50%;
  margin-top: 20px;
}

```


## OUTPUT:
"C:\Users\admin\Downloads\Gemini_Generated_Image_vulhaqvulhaqvulh.png"
"C:\Users\admin\Downloads\Gemini_Generated_Image_5k0zd15k0zd15k0z.png"





## RESULT:
The program for creating Portfolio using HTML and CSS is executed successfully.
