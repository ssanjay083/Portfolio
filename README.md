# Ex01 Portfolio
## Date: 31-01-2026

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
```
<html>
<head>
    <title>My Resume Portfolio</title>

    <style>
         .main-header {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 32px;
            font-weight: bold;
            letter-spacing: 2px;
        }     

        * {
            font-family: Arial;
            box-sizing: border-box;
        }

        body {
            background-color: white;
            margin: 0;
        }

        nav {
            background-color: black;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: yellow;
        }

        section {
            width: 90%;
            margin: 20px auto;
        }

        table {
            width: 90%;
            margin: auto;
            border-collapse: collapse;
        }

        td, th {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
 

        .title {
            font-weight: bold;
            font-size: 18px;
            background-color: #f2f2f2;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
        }

        footer {
            text-align: center;
            margin: 20px;
            font-size: 14px;
            font-weight: bold;
        }
    </style>
</head>

<body>
<div class="main-header">
    MY RESUME PORTFOLIO
</div>
<nav>
    <a href="#intro">Introduction</a>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#education">Education</a>
    <a href="#contact">Contact</a>
</nav>
<section id="intro">
    <table>
        <tr>
            <td colspan="2" class="title">Introduction</td>
        </tr>

        <tr>
            <td>
                <img src="prof.jpeg" class="profile-img">
            </td>

            <td>
                <b>Sanjay S</b><br><br>
                Java Developer | Web Developer<br><br>
                Aspiring Software Engineer preparing for placements.
            </td>
        </tr>
    </table>
</section>
<section id="about">
    <table>
        <tr>
            <td class="title">About Me</td>
        </tr>

        <tr>
            <td>
                I am a motivated computer science student with good
                knowledge in Java, Web Development, and DSA.
                I aim to build a successful career in software industry.
            </td>
        </tr>
    </table>
</section>
<section id="skills">
    <table>
        <tr>
            <td colspan="2" class="title">Technical Skills</td>
        </tr>

        <tr>
            <th>Skill</th>
            <th>Level</th>
        </tr>

        <tr>
            <td>Java</td>
            <td>Good</td>
        </tr>

        <tr>
            <td>HTML</td>
            <td>Good</td>
        </tr>

        <tr>
            <td>CSS</td>
            <td>Average</td>
        </tr>

        <tr>
            <td>DSA</td>
            <td>Learning</td>
        </tr>
    </table>
</section>
<section id="projects">
    <table>
        <tr>
            <td colspan="2" class="title">Projects</td>
        </tr>

        <tr>
            <th>Project</th>
            <th>Description</th>
        </tr>

        <tr>
            <td>Student Management System</td>
            <td>Java-based project to manage student records.</td>
        </tr>

        <tr>
            <td>Portfolio Website</td>
            <td>Personal resume website using HTML and CSS.</td>
        </tr>
    </table>
</section>
<section id="education">
    <table>
        <tr>
            <td colspan="4" class="title">Education</td>
        </tr>

        <tr>
            <th>Level</th>
            <th>Institution</th>
            <th>Year</th>
            <th>Percentage</th>
        </tr>

        <tr>
            <td>10th</td>
            <td>High School</td>
            <td>2022</td>
            <td>88%</td>
        </tr>

        <tr>
            <td>12th</td>
            <td>Higher Secondary</td>
            <td>2024</td>
            <td>85%</td>
        </tr>

        <tr>
            <td>B.E CSE</td>
            <td>Saveetha Engineering College</td>
            <td>2024-2028</td>
            <td>80%</td>
        </tr>
    </table>
</section>
<section id="contact">
    <table>
        <tr>
            <td colspan="2" class="title">Contact Details</td>
        </tr>

        <tr>
            <td>Email</td>
            <td>sanjay@gmail.com</td>
        </tr>

        <tr>
            <td>Mobile</td>
            <td>9876543210</td>
        </tr>

        <tr>
            <td>Location</td>
            <td>Tamil Nadu</td>
        </tr>
    </table>
</section>
<footer>
    © 2026 Sanjay S | Resume Portfolio
</footer>
</body>
</html>

```


## OUTPUT
<img width="1593" height="1113" alt="Screenshot 2026-02-04 134321" src="https://github.com/user-attachments/assets/76a34e49-9a91-4773-a3cf-689ddcf0c0be" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
