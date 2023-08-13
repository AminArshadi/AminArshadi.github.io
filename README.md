<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amin Arshadi's Personal Website</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

    <style>
        body, html {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: black;
            scroll-behavior: smooth;
        }

        #homepage {
            background-color: rgba(26, 59, 112, 0.8);
            color: #fff;
            text-align: center;
            padding: 50px 0;
        }

        #homepage h1 {
            font-size: 3em;
            font-family: 'Playfair Display', serif;
        }

        #profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-top: 20px;
        }

        nav a, #homepage p a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
            transition: all 0.3s ease;
        }

        .flex-container {
            display: flex;
            justify-content: space-between;
            margin: 0 auto;
            max-width: 1200px;
            flex-wrap: wrap;
        }

        section {
            box-sizing: border-box;
            padding: 50px 20px;
            text-align: left;
            background-color: rgba(255, 255, 255, 0.9);
            color: #000;
            margin: 20px;
            border-radius: 10px;
            flex: 1;
            min-width: calc(50% - 40px);
            position: relative;
            overflow: hidden;
            transition: transform 0.3s;
        }

        section:hover {
            transform: translateY(-5px);
        }

        section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 10px;
            background: linear-gradient(90deg, #1a3b70, #f5a623, #1a3b70);
        }

        section h2, #summary h2, #education h2, #experience h2, #projects h2 {
            text-align: center;
            color: #1a3b70;
            font-family: 'Playfair Display', serif;
        }

        footer {
            background-color: black;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        #homepage nav {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        #homepage nav a {
            padding: 10px 10px;
            background-color: #fff;
            color: #1a3b70;
            border-radius: 50px;
            display: inline-block;
            width: 100px;
            height: 30px;
            line-height: 30px;
            text-align: center;
            transition: background-color 0.3s, transform 0.3s;
        }

        #homepage nav a:hover {
            background-color: #f5a623;
            transform: translateY(-5px);
        }

        #homepage p a {
            font-weight: bold;
            position: relative;
            padding: 0 5px;
            transition: transform 0.3s;
        }

        #homepage p a:hover {
            transform: scale(1.05);
        }

        #homepage p a::after {
            content: "";
            position: absolute;
            bottom: -2px;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(90deg, #f5a623, #fff);
            transform: scaleX(0);
            transform-origin: right;
            transition: transform 0.3s;
        }

        #homepage p a:hover::after {
            transform: scaleX(1);
            transform-origin: left;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        #scrollTopBtn {
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 10px 20px;
            background-color: #1a3b70;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: opacity 0.3s;
        }

        #scrollTopBtn:hover {
            opacity: 0.8;
        }
    </style>

</head>

<body>
    <!-- Homepage Section -->
    <section id="homepage">
        <h1>Amin Arshadi</h1>
        <p>
            <a href="tel:+16476172258"><i class="fas fa-phone-alt"></i> (647) 617-2258</a> &middot;
                <a href="mailto:aminarshadi14@gmail.com"><i class="fas fa-envelope"></i> aminarshadi14@gmail.com</a> &middot;
                <a href="https://github.com/AminArshadi" target="_blank"><i class="fab fa-github"></i> GitHub</a> &middot;
                <a href="https://www.linkedin.com/in/amin1410arshadi" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
        </p>
        <nav>
            <a href="#summary">Summary</a>
            <a href="#education">Education</a>
            <a href="#experience">Experience</a>
            <a href="#projects">Projects</a>
            <a href="#certifications">Certifications</a>
        </nav>
    </section>

    <!-- Summary Section -->
    <div class="flex-container">
        <section id="summary">
            <h2>Summary of Qualifications</h2>
            <h3>Programming Languages:</h3>
            <ul>
                <li>Python, Java, C++, C, Go, R, Prolog, Scheme, JavaScript, HTML, and CSS</li>
            </ul>
            <h3>Frameworks and Tools:</h3>
            <ul>
                <li>Robot, Selenium</li>
                <li>Git, GitLab, GitHub, Jira, Bitbucket, SVN</li>
                <li>MongoDB, Firebase, SQLite</li>
                <li>Apache, Docker, Jenkins, CircleCI</li>
                <li>APT, Grep, Make, CMake, FPGA</li>
                <li>Android Studio, Jupiter Notebook</li>
            </ul>
            <h3>Libraries:</h3>
            <ul>
                <li>OpenCV, Scikit Learn, NumPy, TensorFlow, PyTorch, Pandas, PyMongo, Matplotlib, and OS</li>
            </ul>
            <h3>Other skills:</h3>
            <ul>
                <li>Shell scripting, Bash scripting</li>
                <li>SSH, Protocol Buffers, gRPC, Networking Protocols</li>
                <li>Linux, Windows, macOS</li>
            </ul>
        </section>

        <!-- Education Section -->
        <section id="education">
            <h2>Education</h2>
            <h3>University of Ottawa, ON</h3>
            <p>September / 2020 - December / 2024</p>
            <p>Bachelor of Science with Honours in Computer Science</p>
            <p>CGPA: 9.55/10 (Dean’s Honour List)</p>
            <h4>Relevant Courses:</h4>
            <p>Intro to Computing I, Intro to Computing II, Digital Systems I, Data Structures and Algorithms, Intro to Software Engineering, Computer Architecture I, Discrete Structures, Programming Paradigms, Statistics for Engineers, Advances Programming concepts with C++, Design Analysis Algorithms I, Programming Languages Concepts, Intro to Formal Languages, Operating Systems, Intro to Data Communication and Networking</p>
        </section>
    </div>

    <!-- Work Experience Section -->
    <section id="experience">
        <h2>Work Experience</h2>
        <h3>Linux Software Engineer, Ross Video Limited, Ottawa, ON</h3>
        <p>January / 2023 – May / 2023</p>
        <ul>
            <li>Built customized Linux-based operating systems for embedded systems and automated the build process with tools such as FPGA and Make.</li>
            <li>Transferred PhabrixQX’s audio and video functionalities to Ross Video's MC1-UHD product, reducing the cost by over $8,000 per unit.</li>
            <li>Developed the functionalities of RossTalk (a text-based protocol that allows control of the Switcher from an external device).</li>
        </ul>

        <h3>Software Engineer, Ross Video Limited, Ottawa, ON</h3>
        <p>May / 2022 – September / 2022</p>
        <ul>
            <li>Worked with Python-based automation frameworks (mainly Robot) and libraries to automate test cases for Ross Video’s products (Gator-Sync, MC1-UHD, and Switcher), resulting in a 20% increase in overall software performance and a 25% reduction in software bugs.</li>
            <li>Reduced the running time of a program to capture frames on Gator-Sync from 10 to 2.4 seconds per frame, resulting in a 30% decrease in resource utilization.</li>
            <li>Designed and developed a robust image defect detection model, enabling the identification and saving of images with defects to the network for further analysis, and debugging, which improved overall software stability by 45% and reduced the number of defects by 50%.</li>
            <li>Streamlined test execution, reporting, and debugging by executing test plans, reporting bugs, and verifying fixes to ensure timely and accurate delivery of high-quality software products.</li>
        </ul>

        <h3>Security Software Developer, HANECS GmbH, Ottawa, ON</h3>
        <p>October / 2021 – February / 2022</p>
        <ul>
            <li>Contributed to the development of the "Cybersecurity for Automotive" educational package offered by HANECS GmbH, which saw a 25% increase in student enrolment and a 10% improvement in student retention rates compared to previous offerings.</li>
            <li>Collaborated with team members to integrate both symmetric and asymmetric cryptography algorithms, including DES, AES, RSA, ECC, and SHF, which improved data encryption and decryption by up to 75% and ensured compliance with industry standards.</li>
            <li>Successfully delivered the software products within budget constraints, contributing to the overall success of the project and receiving commendations from both management and clients.</li>
        </ul>

        <h3>Python Developer, HANECS GmbH, Ottawa, ON</h3>
        <p>June / 2021 – September / 2021</p>
        <ul>
            <li>Developed Python for Automotive educational package offered by HANECS GmbH (<a href="https://www.hanecs.de/en/academy-en/" target="_blank">https://www.hanecs.de/en/academy-en/</a>).</li>
            <li>Applied university-level problem-solving skills, including Dijkstra, Prime/Jarnik, and Kruskal algorithms, to find solutions to a real-life mapping problem, resulting in a 60% reduction in the program running time and a 30% improvement in overall software efficiency and accuracy.</li>
            <li>Conducted extensive testing and debugging, reducing the number of bugs and errors by 30% and improving overall software stability by 20%.</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <h3>Paper Scanner (Computer Vision):</h3>
        <p>Utilized advanced image processing techniques as well as OpenCV and NumPy libraries in this project for high-quality scanning and digitization of paper documents.</p>
        
        <h3>Colour, Lane, and Shape Detector (Computer Vision):</h3>
        <p>Used OpenCV and NumPy to detect and classify objects based on colour, lane markings, and shape in images and videos, which involved developing a pipeline that processes input from a camera or video stream and outputs the detected objects with their corresponding labels.</p>
        
        <h3>Weather Forecaster (Machine Learning):</h3>
        <p>Worked on a program that predicts weather patterns and conditions by leveraging historical weather data for accurate forecasting.</p>
        
        <h3>Data Clustering Program (Machine Learning):</h3>
        <p>Created a project in which the DBSCAN algorithm for unsupervised clustering of high-dimensional data was utilized and advanced clustering techniques to partition the data into clusters based on similarity and density are used.</p>
        
        <h3>Service Booking Android App:</h3>
        <p>Developed an application that allows users to create accounts, book services, and rate their experiences, with three different types of accounts available - admin, employee, and customer - each with different functionalities, and utilizes Firebase's real-time database to store user information and service requests, enabling real-time updates for both users and service.</p>
        
        <h3>Web App:</h3>
        <p>Contributed to the development of a web application that has a client-server architecture where the client side of the web application is built using HTML, CSS, and JavaScript. The server side is built using a combination of various technologies such as Node.js, Express, and MongoDB.</p>
    </section>

    <!-- Certifications Section -->
        <section id="certifications">
            <h2>Certifications</h2>
            <p>Details about certifications will go here.</p>
            <!-- You can add more content related to certifications here. -->
        </section>

    <footer>
        <div class="container">
            © 2023 Amin Arshadi. All rights reserved.
        </div>
    </footer>

    <script>
        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                document.getElementById("scrollTopBtn").style.display = "block";
            } else {
                document.getElementById("scrollTopBtn").style.display = "none";
            }
        }

        function scrollToTop() {
            document.body.scrollTop = 0; // For Safari
            document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
        }
    </script>

    <!-- Scroll to Top Button -->
    <button id="scrollTopBtn" onclick="scrollToTop()" style="display:none;"><i class="fas fa-arrow-up"></i></button>

</body>

</html>
