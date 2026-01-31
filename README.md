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
<!DOCTYPE html>
<html>
<head>
    <title>My Resume Portfolio</title>

    <style>

        * {
            font-family: Arial;
            box-sizing: border-box;
        }

        body {
            background-color: white;
            margin: 0;
        }

        table {
            width: 90%;
            margin: 20px auto;
            border-collapse: collapse;
        }

        td, th {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }

        .header td {
            font-size: 24px;
            font-weight: bold;
            border: none;
        }

        .menu td {
            font-size: 16px;
            border: none;
            font-weight: bold;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 70%;
        }

        .title {
            font-weight: bold;
            font-size: 18px;
            background-color: #f2f2f2;
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

    <table class="header">
        <tr>
            <td>MY RESUME PORTFOLIO</td>
        </tr>
    </table>

    <table class="menu">
        <tr>
            <td>Profile</td>
            <td>Technical Skills</td>
            <td>Education</td>
            <td>Contact</td>
        </tr>
    </table>

    <table>
        <tr>
            <td colspan="2" class="title">Profile</td>
        </tr>

        <tr>
            <td>
                <img src="C:\Users\admin\Desktop\mwa exp\prof.jpeg" class="profile-img">
            </td>

            <td>
                <b>Sanjay S</b><br><br>
                Java Developer | Web Developer<br><br>

                I am a motivated student with good knowledge
                in Java and Web Development. I am preparing
                myself for software company requirements.
            </td>
        </tr>
    </table>

    <table>
        <tr>
            <td colspan="2" class="title">Technical Skills</td>
        </tr>

        <tr>
            <th>Skill</th>
            <th>Level (For Company)</th>
        </tr>

        <tr>
            <td>Java</td>
            <td>Good (Industry Ready)</td>
        </tr>

        <tr>
            <td>HTML</td>
            <td>Good (Frontend Basics)</td>
        </tr>

        <tr>
            <td>CSS</td>
            <td>Average (Design Level)</td>
        </tr>

        <tr>
            <td>DSA</td>
            <td>Learning (Placement Level)</td>
        </tr>
    </table>

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
            <td>10th Standard</td>
            <td>High School</td>
            <td>2021 - 2022</td>
            <td>88%</td>
        </tr>

        <tr>
            <td>12th Standard</td>
            <td>Higher Secondary School</td>
            <td>2023 - 2024</td>
            <td>85%</td>
        </tr>

        <tr>
            <td>B.E (CSE)</td>
            <td>Saveetha Engineering College</td>
            <td>2024 - 2028</td>
            <td>80%</td>
        </tr>
    </table>

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

    <footer>
        © 2026 Sanjay S | Resume Portfolio
    </footer>

</body>
</html>

```


## OUTPUT
<img width="1860" height="1059" alt="image" src="https://github.com/user-attachments/assets/4c4d65ec-11b3-435c-b617-2698a96562e0" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
