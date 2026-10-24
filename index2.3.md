Task: Convert the previous introduction page into clean and structured HTML.

Objective

To organize a personal introduction webpage using div containers, unique id attributes, reusable class attributes, and custom data-* attributes.

Complete HTML Code

Save this file as index.html.

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shubham Yadav - Personal Introduction</title>
</head>

<body>

    <!-- Header Section -->
    <div id="header" class="section header-section"
         data-page="personal-introduction">

        <h1 id="student-name">Shubham Yadav</h1>

        <p class="intro-text">
            <strong>B.Tech Computer Science Engineering Student</strong>
            <br>
            Invertis University
        </p>

        <p>Welcome to my personal introduction webpage.</p>

    </div>

    <hr>

    <!-- About Section -->
    <div id="about" class="section about-section">

        <h2>About Me</h2>

        <p id="about-description" class="content-text">
            Hello! My name is Shubham Yadav. I am pursuing B.Tech
            in Computer Science Engineering at Invertis University.
            I am interested in programming, technology, and web
            development.
        </p>

        <p class="content-text">
            I enjoy learning new skills, solving problems, and
            creating useful projects. My goal is to become a
            successful software developer.
        </p>

    </div>

    <hr>

    <!-- Education Section -->
    <div id="education" class="section education-section">

        <h2>Education</h2>

        <div id="graduation" class="education-item">
            <h3>B.Tech in Computer Science Engineering</h3>
            <p><strong>University:</strong> Invertis University</p>
            <p><strong>Course:</strong> Bachelor of Technology</p>
        </div>

        <div id="school-education" class="education-item">
            <h3>Senior Secondary Education</h3>
            <p><strong>School:</strong> Lord Academy Secondary School</p>
            <p><strong>Qualification:</strong> Class 12</p>
        </div>

    </div>

    <hr>

    <!-- Skills Section -->
    <div id="skills" class="section skills-section">

        <h2>My Skills</h2>

        <div id="technical-skills" class="skill-group">
            <h3>Technical Skills</h3>
            <p class="content-text">
                HTML, Basic Programming, Computer Fundamentals,
                and Web Development Basics.
            </p>
        </div>

        <div id="personal-skills" class="skill-group">
            <h3>Personal Skills</h3>
            <p class="content-text">
                Teamwork, Communication, Problem-Solving,
                Time Management, and Quick Learning.
            </p>
        </div>

        <div id="hobbies" class="skill-group">
            <h3>Hobbies and Interests</h3>
            <p class="content-text">
                Learning new technologies, practising coding,
                exploring computers, and working on creative projects.
            </p>
        </div>

    </div>

    <hr>

    <!-- Contact Section -->
    <div id="contact" class="section contact-section">

        <h2>Contact Me</h2>

        <p class="content-text">
            I am interested in learning new technologies,
            collaborating with others, and working on new projects.
        </p>

        <p id="contact-message">
            Thank you for visiting my personal introduction page!
        </p>

    </div>

    <hr>

    <!-- Footer Section -->
    <div id="footer" class="section footer-section">

        <p>
            <em>Keep learning, keep growing.</em>
        </p>

        <p>Copyright &copy; 2026 Shubham Yadav</p>

    </div>

</body>

</html>

Explanation of HTML Attributes

1. ID Attribute

The id attribute gives a unique identity to an HTML element. For example, id="header" identifies the Header section.

2. Class Attribute

The class attribute groups elements that can share the same styling or behavior. For example, class="content-text" is used for multiple paragraphs.

3. Custom Data Attribute

The data-* attribute stores custom information on an HTML element. In this assignment, data-page="personal-introduction" is used in the Header section.

4. Div Element

The div element groups related HTML elements into separate sections, making the page easier to organize and maintain.

Output

The webpage contains these sections:

Header

About Me

Education

Skills

Contact Me

Footer

Conclusion

This assignment helped me understand how to create clean and structured HTML using div containers, unique IDs, reusable classes, and custom data-* attributes. I also learned how meaningful names, comments, and proper indentation improve code readability and maintenance.

Submission

Save the HTML code as index.html.

Open the file in a browser using Live Server.

Take a screenshot of the webpage.

Submit both index.html and the screenshot.

Screenshot filename: Assignment-2.3-Screenshot.png