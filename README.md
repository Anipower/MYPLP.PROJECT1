# MYPLP.PROJECT1
August Cohort Portfolio Challenge! 🚀
Your task is to create a personal portfolio website that highlights your skills, background, and projects. Make sure your portfolio includes the following sections:

Programming Languages: List the programming languages you are proficient in.
About Section: Provide a brief introduction about yourself, your passion, and what drives you.
Educational Background: Include a section where visitors can download your CV.
Interests: Share your interests and what excites you in the tech world.
Projects: Link to the projects you’ve worked on with brief descriptions.
Contact Form: Add a contact form to make it easy for potential collaborators or employers to get in touch with you.
🛠️ Guidelines
Skills: Use HTML and CSS to build your portfolio. Feel free to use additional technologies if you’re comfortable with them.
Work Solo: This is an individual challenge, so showcase your personal skills and creativity.
Submission: Your completed portfolio should be pushed to a public GitHub repository.
📁 How to Submit
Create Your Portfolio: Develop your portfolio website and make sure it includes all required sections.
Push to GitHub: Ensure your project is pushed to a public GitHub repository.
Update README: Fill out your README.md file with the necessary information.
Submit your repo to this form: https://forms.gle/KyyHHaya5sWfcRZH6.
💼 Example Sections
## 📝 About Me
Hi! I'm [Your Name], a passionate web developer...

## 🎓 Educational Background
I hold a degree in [Your Degree] from [Your University]. [Download My CV](link-to-your-cv)

## 💡 Interests
- **Web Development**: Exploring the latest trends...
- **Tech Innovations**: Staying updated with advancements...

## 🛠️ Projects
- [Project 1](link-to-project1): Brief description...
- [Project 2](link-to-project2): Brief description...

## 📬 Contact Me
Feel free to reach out! [Contact Form](link-to-your-contact-form)

HERE IS MY ANSWERS TO THIS PROJECT
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anietie Akpan Ubom - Web Developer Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Anietie Akpan Ubom</h1>
        <p>Web Developer</p>
    </header>

    <section id="about">
        <h2>📝 About Me</h2>
        <p>Hi! I'm Anietie Akpan Ubom aka (Anipower), a passionate web developer with a knack for creating functional and aesthetically pleasing websites. I am constantly exploring new technologies to enhance my skills and provide better solutions.</p>
    </section>

    <section id="education">
        <h2>🎓 Educational Background</h2>
        <p>I hold a degree in Computer Science from Bestower University and a Higher National Diploma in Electrical/Electronics Engineering from Heritage Polytechnic.</p>
        <a href="file:///C:/Users/PC/Documents/ANITECH.pdf" target="_blank" class="btn">Download My CV</a>
    </section>

    <section id="interests">
        <h2>💡 Interests</h2>
        <ul>
            <li><strong>Web Development</strong>: Exploring the latest trends in development.</li>
            <li><strong>Tech Innovations</strong>: Staying updated with advancements in technology.</li>
            <li><strong>Artificial Intelligence</strong>: Diving into machine learning and AI technologies.</li>
            <li><strong>Electronics</strong>: Enthusiast in building simple electronics and IoT devices.</li>
            <li><strong>Problem-Solving</strong>: Enjoy working on solutions for complex challenges.</li>
        </ul>
    </section>

    <section id="projects">
        <h2>🛠️ Projects</h2>
        <ul>
            <li><a href="https://anipower.com.ng" target="_blank">Project 1</a>: A web development project that showcases my skills in creating dynamic websites.</li>
            <li><a href="link-to-project2" target="_blank">Project 2</a>: A software development project demonstrating back-end functionality.</li>
        </ul>
    </section>

    <section id="contact">
        <h2>📬 Contact Me</h2>
        <p>Feel free to reach out!</p>
        <ul>
            <li>Phone: <a href="tel:+2349028559540">+2349028559540</a></li>
            <li>Website: <a href="http://www.anipower.com.ng" target="_blank">www.anipower.com.ng</a></li>
            <li>Email: <a href="mailto:anieub3@gmail.com">anieub3@gmail.com</a> | <a href="mailto:reachout@anipower.com.ng">reachout@anipower.com.ng</a></li>
            <li><a href="https://wa.link/mmjk3n" target="_blank" class="btn">Contact Form</a></li>
        </ul>
    </section>
</body>
</html>



CSS

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    padding: 20px;
}

header {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: #fff;
}

header h1 {
    margin-bottom: 10px;
    font-size: 36px;
}

header p {
    font-size: 20px;
}

section {
    margin: 20px 0;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

section h2 {
    margin-bottom: 15px;
    color: #333;
}

ul {
    list-style-type: disc;
    margin-left: 20px;
}

ul li {
    margin-bottom: 10px;
}

.btn {
    display: inline-block;
    background-color: #333;
    color: #fff;
    padding: 10px 15px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 10px;
}

.btn:hover {
    background-color: #555;
}

a {
    color: #333;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}










