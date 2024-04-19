<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mbalenhle Mbambo - Landing Page</title>
    <link rel="stylesheet" href="styles/landingpage.css">
    <style>

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: gray;
            color: #333;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        /* Header Styles */
        header {
            background-color: powderblue;
            color: black;
            padding: 20px 0;
            text-align: center;
        }
        /* Footer Styles */
        footer {
            background-color: powderblue;
            color: black;
            padding: 10px 0;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        /* Section Styles */
        section {
            padding: 50px 0;
            text-align: center;
        }
        /* Introduction Section Styles */
        #introduction img {
            border-radius: 50%;
            width: 200px;
            height: 200px;
            margin-bottom: 20px;
        }
        /* Portfolio Section Styles */
        .project {
            margin-bottom: 30px;
            
        }
        .project img {
            max-width: 100%;
            border-radius: 5px;
        }
       
        blockquote {
            font-style: italic;
            margin: 0;
        }
        /* Contact Section Styles */
        #contact ul {
            list-style: none;
            padding: 0;
        }
        #contact ul li {
            margin-bottom: 10px;
        }
        /* Social Media Section Styles */
        #social-media a {
            display: inline-block;
            margin: 0 10px;
            color: #fff;
            text-decoration: none;
            border: 2px solid #343a40;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }
        #social-media a:hover {
            background-color: #343a40;
            color: #fff;
        }
        /* Call-to-Action Section Styles */
        #cta a {
            display: inline-block;
            background-color: #343a40;
            color: #fff;
            text-decoration: none;
            padding: 15px 30px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        #cta a:hover {
            background-color: #1e2124;
        }
        .contact {
        display: flex; 
    }
    .call {
        width: 50%; 
        padding: 20px;
        box-sizing: border-box;
    }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Mbalenhle Mbambo</h1>
    </header>

    
    <div class="container">
        
        <section id="introduction">
            <h2>About Me</h2>
            <p>Hello, I'm Mbalenhle Mbambo. Welcome to my landing page!</p>
            <img src="pictures/WhatsApp Image 2024-04-17 at 13.59.48_47ac4a9d.jpg" alt="Mbalenhle Mbambo">
        </section>

        
        <section>
        
                <h2>EDUCATION</h2>
            <p><ul>
            <li> Qualification: Diploma in Information Technology</li>
            <li>University: Vaal University of Technology</li>
            <li> Graduation Year: 2024</li>
            </ul></p>

            <h2>SKILLS</h2>
            <p><ul></ul>
                My academic and professional experiences have equipped me with a diverse skill set in IT, including but not limited to:
        
        Programming Languages: Proficient in languages such as 
        <li>Python</li>
        <li>JavaScript</li>
        <li>SQL</li>
        
        <li><b>Web Development</b>: Experience in front-end and back-end web development, utilizing HTML and CSS.</li>
        <li><b>Database Management</b>: Skilled in designing, implementing, and managing databases using technologies like MySQL.</li>
        <li><b>Networking</b>: Understanding of networking principles, including TCP/IP, routing, and network security.</li>
        <li><b>Project Management</b>: Capable of managing IT projects from conception to implementation, ensuring timely delivery and adherence to requirements.</li>
        </ul></p>
            </ul>
        </section>

        <!-- Portfolio Section -->
        <section class="section">
            <h2>Portfolio</h2>
            <p>The following are the personal projects i have worked on so far!!!.</p>
            <h2>PROJECT 1</h2>
            <div class="project">
                <img src="pictures/project 1.png" alt="Project 1">
                <li>This is an ecommerce website whereby users were required to open an account first before proceeding</li>
                <li>After opening an account the user must browse through the menu. </li>
                <li>The user is now required to make an order were they pick items and add them to their shopping cart.</li>
                <li>The final step is were the user add their card details in order to make a purchase.</li>

            </div>
            <div class="project">
                <h2>PROJECT 2</h2>
                <img src="pictures/project 2.png" alt="Project 2">
                <li>This is a temperature Converter ,it converts temperature to either degrees Fahrenheit or degrees Celsius</li>
                <li>If the user click convert without entering any input ,there will be an error message telling the user to enter temperature</li>
            </div>
            
        </section>
                </blockquote>
            </div>

        <!-- Contact Section -->
        
        <section class="contact" id="contact">
            <div class="call"> 
                <img src="pictures/OIP.jpeg">
            </div>
          <div class="call">
            <h2>Contact</h2>
            <p>Get in touch with me:</p>
            <ul>
                <li>Email: mbalenhlebongekile032@gmail.com</li>
                <li>Phone: +27 71 216 7068</li>
                <li>
                    Social Media:
                    <p>linkedIn</p>
                    <a href="#">www.linkedin.com/in/mbalenhle-mbambo-85b55726b</a><br>
                    <p>GITHUB</p>
                    <a href="#">Mbalenhle084.com</a>
                </li>
            </ul>
        </div>
        </section>

        <!-- Call-to-Action Section -->
        <section id="cta">
            <h2>Call-to-Action</h2>
            <p>Ready to work together?</p>
            <a href="0712167068">Contact Me</a>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Mbalenhle Mbambo. All rights reserved.</p>
    </footer>
</body>
</html>
