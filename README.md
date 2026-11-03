# Ex01 Portfolio
## Date:02-11-2026

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
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sathana V - Personal Portfolio</title>
</head>

<body>

    <!-- HEADER SECTION -->

    <center>

        <h1>MY PERSONAL PORTFOLIO</h1>

        <h3>Professional Profile</h3>

        <hr>

        <h3 id="greeting"></h3>

        <!-- PROFILE PHOTO -->

        <img src="C:\Users\admin\exp1\Screenshot 2026-11-02 152800.png"           
             alt="Sathana Profile Photo"
             width="180"
             height="180">

        <h2>SATHANA V</h2>

        <h3>B.Tech Information Technology Student</h3>

        <p>
            Aspiring IT Professional | Technology Enthusiast
        </p>

        <p>
            <b>Current Date & Time:</b>
            <span id="datetime"></span>
        </p>

        <hr>

        <!-- NAVIGATION -->

        <a href="#about">About Me</a> |
        <a href="#education">Education</a> |
        <a href="#skills">Skills</a> |
        <a href="#projects">Projects</a> |
        <a href="#certifications">Certifications</a> |
        <a href="#contact">Contact</a>

        <hr>

    </center>


    <!-- 1. ABOUT ME -->

    <center>

        <h2 id="about">1. About Me</h2>

        <p>
            I am a dedicated and enthusiastic B.Tech Information
            Technology student with a strong interest in technology,
            programming and software development.
        </p>

        <p>
            I am passionate about learning new technologies,
            exploring innovative ideas and developing practical
            solutions through academic projects.
        </p>

        <p>
            My goal is to enhance my technical knowledge,
            improve my professional skills and build a
            successful career in the IT industry.
        </p>

        <hr>

    </center>


    <!-- 2. EDUCATIONAL QUALIFICATION -->

    <center>

        <h2 id="education">2. Educational Qualification</h2>

        <table border="1" cellpadding="10" cellspacing="0">

            <tr>
                <th>Qualification</th>
                <th>Institution</th>
                <th>Year</th>
                <th>Percentage / CGPA</th>
            </tr>

            <tr>
                <td>B.Tech Information Technology</td>
                <td>Saveetha Engineering College</td>
                <td>2024 - 2028</td>
                <td>8.00</td>
            </tr>

            <tr>
                <td>Higher Secondary (HSC)</td>
                <td>Dharani Matric Higher Secondary School</td>
                <td>2024</td>
                <td>95%</td>
            </tr>

            <tr>
                <td>Secondary School (SSLC)</td>
                <td>Dharani Matric Higher Secondary School</td>
                <td>2022</td>
                <td>100%</td>
            </tr>

        </table>

        <hr>

    </center>


    <!-- 3. TECHNICAL SKILLS -->

    <center>

        <h2 id="skills">3. Technical Skills</h2>

        <p>
            • HTML<br>
            • CSS<br>
            • Python Programming<br>
            • Java Programming<br>
            • JavaScript<br>
            • SQL Database<br>
            • Artificial Intelligence<br>
            • Geographic Information System (GIS)<br>
            • Google Earth Engine
        </p>

        <button onclick="showSkills()">
            View Skills Summary
        </button>

        <p id="skillResult"></p>

        <hr>

    </center>


    <!-- 4. SOFT SKILLS -->

    <center>

        <h2>4. Soft Skills</h2>

        <p>
            • Communication Skills<br>
            • Teamwork and Collaboration<br>
            • Problem Solving<br>
            • Time Management<br>
            • Critical Thinking<br>
            • Adaptability
        </p>

        <hr>

    </center>


    <!-- 5. ACADEMIC PROJECTS -->

    <center>

        <h2 id="projects">5. Academic Projects</h2>

        <h3>Project 1: Groundwater Potential Zonation</h3>

        <p>
            This project focuses on identifying groundwater
            potential zones using GIS-based Multi-Criteria Analysis.
        </p>

        <p>
            It uses geographical parameters and spatial data
            to analyze groundwater availability and support
            sustainable water resource management.
        </p>

      
        <button onclick="showProjects()">
            View Project Summary
        </button>

        <p id="projectResult"></p>

        <hr>

    </center>


    <!-- 6. CERTIFICATIONS -->

    <center>

        <h2 id="certifications">6. Certifications</h2>

        <p>
            1. NPTEL<br>
            2. COURSERA<br>
            3. AWS
        </p>

        <hr>

    </center>


    <!-- 7. CAREER OBJECTIVE -->

    <center>

        <h2>7. Career Objective</h2>

        <p>
            To pursue a challenging career in the IT industry
            where I can apply my technical knowledge, develop
            professional skills, learn emerging technologies
            and contribute effectively to organizational growth.
        </p>

        <hr>

    </center>


    <!-- 8. CONTACT INFORMATION -->

    <center>

        <h2 id="contact">8. Contact Information</h2>

        <p>
            <b>Name:</b> SATHANA V
        </p>

        <p>
            <b>Email:</b>
            <a href="mailto:sathana.v1313@gmail.com">
                sathana.v1313@gmail.com
            </a>
        </p>

        <p>
            <b>Phone:</b> +91 9363528236
        </p>

        <p>
            <b>Location:</b> Tamil Nadu, India
        </p>

        <p>
            <b>LinkedIn:</b>
            <a href="https://www.linkedin.com/in/sathana-v-59295832a/"
               target="_blank">
                https://www.linkedin.com/in/sathana-v-59295832a/
            </a>
        </p>

        <p>
            <b>GitHub:</b>
            <a href="https://github.com/SATHANA1313"
               target="_blank">
               https://github.com/SATHANA1313
            </a>
        </p>

        <hr>

    </center>


    <!-- FOOTER SECTION -->

    <center>

        <h3>Thank You for Visiting My Portfolio!</h3>

        <p>
            I look forward to learning, growing
            and creating innovative solutions.
        </p>

        <hr>

        <p>
            Copyright &copy;
            <span id="year"></span>
            SATHANA V. All Rights Reserved.
        </p>

    </center>


    <!-- JAVASCRIPT SECTION -->

    <script>

        // 1. Welcome Message

        function displayGreeting() {

            let currentHour = new Date().getHours();

            let message;

            if (currentHour < 12) {

                message = "Good Morning! Welcome to My Portfolio";

            }

            else if (currentHour < 17) {

                message = "Good Afternoon! Welcome to My Portfolio";

            }

            else {

                message = "Good Evening! Welcome to My Portfolio";

            }

            document.getElementById("greeting").innerHTML = message;

        }


        // 2. Live Date and Time

        function displayDateTime() {

            let today = new Date();

            document.getElementById("datetime").innerHTML =
                today.toLocaleString();

        }

        displayDateTime();

        setInterval(displayDateTime, 1000);


        // 3. Technical Skills Summary

        function showSkills() {

            let totalSkills = 9;

            document.getElementById("skillResult").innerHTML =
                "Total Technical Skills: " + totalSkills;

        }


        // 4. Academic Project Summary

        function showProjects() {

            document.getElementById("projectResult").innerHTML =
                "Total Academic Projects: 2" +
                "<br>Project 1: Groundwater Potential Zonation" +
                "<br>Project 2: Student Performance Prediction";

        }


        // 5. Automatic Copyright Year

        document.getElementById("year").innerHTML =
            new Date().getFullYear();


        // 6. Display Greeting

        displayGreeting();

    </script>

</body>

</html>
```
## OUTPUT

![alt text](<Screenshot (130).png>)
![alt text](<Screenshot (131).png>)
![alt text](<Screenshot (132).png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.