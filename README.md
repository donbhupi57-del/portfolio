
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio</title>

    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

    

        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            color: #ad3333;
        }

       

        header {
            background: #07b524;
            color: rgba(255, 255, 255, 0.506);
            padding: 15px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h2 {
            font-size: 22px;
        }

        nav a {
            color: rgb(238, 242, 26);
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
        }



        .class1 {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 50px 5%;
            min-height: 280px;
            text-shadow: #07b524;
            text-size-adjust:initial;
        }

        .hero h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        .hero h2 {
            color: #ff725e;
            font-size: 38px;
            margin-bottom: 15px;
        }

        .hero p {
            color: #777;
            font-size: 14px;
        }

        .profile {
            width: 230px;
            height: 190px;
            border-radius: 50%;
            background: #c8e0ff;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 100px;
        }


        section {
            padding: 25px 3%;
        }

        section h2 {
            font-size: 24px;
            margin-bottom: 15px;
        }

     

        #about p {
            font-size: 13px;
            line-height: 1.7;
            color: #555;
        }

       

        .skills-container {
            display: flex;
            gap: 20px;
            padding: 10px 20px;
        }

        .skill {
            
            background: #f31383;
            color: white;
            text-align: center;
            padding: 18px;
            border-radius: 6px;
            font-size: 15px;
           
        }

        

       

        .projects-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }

        .project {
            background: white;
            width: 65%;
            min-height: 120px;
            padding: 20px;
            text-align: center;
            border-radius: 6px;
         
        }


        .project p {
            color: #777;
            font-size: 13px;
        }

      

        .contact-form {
            background: white;
            width: 320px;
            margin: auto;
            padding: 20px;
            border-radius: 6px;
        }

        .contact-form label {
            display: block;
            font-size: 13px;
            margin-top: 10px;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #0750b5;
            border-radius: 4px;
        }

        .contact-form textarea {
            height: 80px;
        }

        .contact-form button {
            width: 100%;
            padding: 10px;
            margin-top: 12px;
            background: #0750b5;
            color: white;
            
        }



        footer {
            background: #0750b5;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 13px;
        }


        .top-button {
            position: fixed;
            bottom: 15px;
            right: 15px;
            background: #0750b5;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 4px;
            font-size: 12px;
        }

      

       

            header {
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 5px;
            }

            .hero {
                flex-direction: column-reverse;
                text-align: center;
                gap: 25px;
            }

            .hero h1 {
                font-size: 30px;
            }

            .hero h2 {
                font-size: 27px;
            }

            .skills-container {
                flex-direction: column;
            }

            .project {
                width: 95%;
            }
     
            .img1{
                width: 200px;
                height: 200px;
                border-radius: 50%;
                object-fit: cover ;
                border-style: solid ;
                border-color: #abd0ae;
            }
        

       

            .profile {
                width: 170px;
                height: 150px;
                font-size: 75px;
            }

    .butt1{
       color: #1a1010;
       position: relative;
       left: 1700px;
       top: 10px;
       size: 200px;
       font-size: 20px;
       background-color: #ad3333;
    }


        

    </style>
</head>

<body id="top">

   

    <header>

        <h2>My Portfolio</h2>

        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>

    </header>


    

    <div class="class1">

        <div>
            <h1>Hi, I am</h1>

            <h2>Bhupender Saini</h2>

            <p>
                Aspiring Web Developer | B.Tech CSE Student
            </p>

        </div>

        <div>
            <img src="profile.jpg.jpg" alt="img" class="img1">
            
        </div>

    </div>


    

    <section id="about">

        <h2>About Me</h2>

        <p>
            Hello! My name is Bhupender, and I am currently
            learning web development. I am interested in
            programming, technology and creating interactive
            websites. My goal is to improve my skills and
            build useful web projects.
        </p>

    </section>


   

    <section id="skills">

        <h2>My Skills</h2>

        <div class="skills-container">

            <div class="skill">
                <h3>HTML</h3>
                <p>Beginner</p>
            </div>

            <div class="skill">
                <h3>CSS</h3>
                <p>Beginner</p>
            </div>

            <div class="skill">
                <h3>Python</h3>
                <p>Learning</p>
            </div>

        </div>

    </section>


 

    <section id="projects">

        <h2>My Projects</h2>

        <div class="projects-container">

            <div class="project">

                <h3>Project 1</h3>

                <p>
                    A simple HTML and CSS webpage.
                </p>

            </div>

            <div class="project">

                <h3>Project 2</h3>

                <p>
                    My personal portfolio website.
                </p>

            </div>

        </div>

    </section>


   

    <section id="contact">

        <h2>Contact Me</h2>

        <form class="contact-form">

            <label>Name:</label>
            <input type="text"
                   placeholder="Enter your name"
                   required>

            <label>Email:</label>
            <input type="email"
                   placeholder="Enter your email"
                   required>

            <label>Message:</label>
            <textarea placeholder="Write your message"
                      required></textarea>

            <button type="submit">
                Send
            </button>

        </form>

    </section>


    

    <footer>

        <p>
            © 2026 Bhupender Saini. All rights reserved.
        </p>

    </footer>

    <div>
    <button class="butt1" > 
        To previous page
    </button>
    </div>


    

</body>
</html>

