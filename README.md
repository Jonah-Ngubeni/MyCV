<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jonah Ben Israel's Personal Webpage</title>
</head>
<body>
    <header>
        <h1>Welcome to Jonah Ben Israel's Personal Webpage</h1>
    </header>

    <section id="bio">
        <h2>About Me</h2>
        <p>
            Hello! My name is Jonah Ben Israel. I have a background in marketing and am currently transitioning into software engineering to embrace the opportunities of the AI revolution. My passion for technology and innovation drives my commitment to mastering this exciting field.
        </p>
        <p>
            With a strong foundation in communication and strategy from my marketing career, I bring a unique perspective to software engineering. I am eager to apply my skills in developing cutting-edge solutions that leverage artificial intelligence to solve real-world problems.
        </p>
        <p>
            I am motivated by the challenge of continuous learning and the potential to contribute to transformative projects. My goal is to build a career at the intersection of technology and creativity.
        </p>
    </section>

    <section id="contact">
        <h2>Contact Details</h2>
        <p><strong>Name:</strong> Jonah Ben Israel</p>
        <p><strong>Contact Number:</strong> +27762999657</p>
        <p><strong>Email:</strong> jonah@example.com</p>
        <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/jonahbenisrael" target="_blank">https://www.linkedin.com/in/jonahbenisrael</a></p>
        <img src="profile.jpg" alt="Jonah Ben Israel's Profile Picture" style="width:150px;height:150px;">
    </section>

    <section id="skills">
        <h2>Skills and Competencies</h2>
        <ul>
            <li>Python Development</li>
            <li>AI and Machine Learning Fundamentals</li>
            <li>Marketing Strategy and Analytics</li>
            <li>Web Development</li>
            <li>Data Analysis</li>
            <li>Communication and Presentation Skills</li>
            <li>Project Management</li>
        </ul>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>Bachelor's Degree in Marketing</strong> - XYZ University</p>
        <p><strong>Software Engineering Bootcamp</strong> - ABC Institute</p>
    </section>

    <section id="experience">
        <h2>Work Experience</h2>
        <ul>
            <li>
                <strong>Marketing Specialist</strong> at DEF Corp
                <ul>
                    <li>Developed and executed marketing campaigns to increase brand awareness and sales.</li>
                    <li>Analyzed market trends to inform strategic decisions.</li>
                </ul>
            </li>
            <li>
                <strong>Freelance Software Developer</strong>
                <ul>
                    <li>Built and deployed web applications as part of my transition into software engineering.</li>
                    <li>Collaborated with clients to create user-friendly solutions.</li>
                </ul>
            </li>
        </ul>
    </section>

    <section id="search">
        <h2>Search My CV</h2>
        <form method="GET" action="/search">
            <label for="search">Search:</label>
            <input type="text" id="search" name="query" placeholder="Enter keyword">
            <button type="submit">Search</button>
        </form>
    </section>

    <section id="contact-form">
        <h2>Contact Me</h2>
        <form method="POST" action="/contact">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea><br>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Jonah Ben Israel. All rights reserved.</p>
    </footer>
</body>
</html>
