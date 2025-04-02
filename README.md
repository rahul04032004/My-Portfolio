<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rahul Raj - Developer Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: white;
            overflow-x: hidden;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4, #fad0c4, #ffdde1);
            background-size: 300% 300%;
            animation: moveBackground 10s infinite alternate;
        }
        @keyframes moveBackground {
            0% { background-position: left; }
            100% { background-position: right; }
        }
        .container {
            text-align: center;
            padding: 50px;
        }
        .title {
            font-size: 3rem;
            font-weight: bold;
        }
        .btn {
            background: #ff6f61;
            padding: 15px 30px;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1.2rem;
            transition: 0.3s;
        }
        .btn:hover {
            background: #ff3d00;
            transform: scale(1.1);
        }
        .section {
            margin-top: 50px;
            padding: 50px;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 20px;
            animation: fadeIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="title">Hello, I'm Rahul Raj</div>
        <p>I'm a Professional Software Developer.</p>
        <button class="btn">Contact Me</button>
        <button class="btn">Get Resume</button>
    </div>
    <div class="section">
        <h2>About Me</h2>
        <p>I am a quick learner with a self-learning attitude. I love to explore new technologies and am passionate about problem-solving.</p>
    </div>
    <div class="section">
        <h2>Experience</h2>
        <p><strong>Software Engineer I</strong> (Jan 2022 - Present)</p>
        <p><strong>FullStack Developer</strong> (Jun 2022 - Jan 2022)</p>
        <p><strong>Self Employed</strong> (Jan 2020 - Present) - Coding and building projects every day.</p>
    </div>
    <div class="section">
        <h2>Skills</h2>
        <p>React, NextJS, Redux, Express, NestJS, MySQL, MongoDB, Docker, AWS</p>
    </div>
    <div class="section">
        <h2>Projects</h2>
        <p><strong>AI Powered Financial App:</strong> Built an AI-powered financial mobile application using OpenAI API and AWS services.</p>
        <p><strong>Travel Agency App:</strong> Designed and developed a full-stack web app for a travel agency using NextJS and NestJS.</p>
        <p><strong>AI Powered Real Estate:</strong> Developed an AI-based real estate app using OpenAI and Replicate API.</p>
    </div>
    <div class="section">
        <h2>Education</h2>
        <p>Bachelor's Degree (2022 - Present) - Lovely Professional University</p>
        <p>Higher Secondary Certificate (2020 - 2022) - St. Xavier High School</p>
        <p>Secondary School Certificate (2008 - 2020) - St. Francis School</p>
    </div>
    <div class="section">
        <h2>Contact</h2>
        <p>Email: rahulraj.040304@gmail.com</p>
        <p>Phone: +91 9334290276</p>
        <p>Location: Deoghar, Jharkhand</p>
    </div>
</body>
</html>
