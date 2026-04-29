# Ex01 Portfolio
## Date: 29/04/2026
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
        <title>Portfolio Page</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
        <link rel="icon" href="https://cdn4.iconfinder.com/data/icons/avatars-21/512/avatar-circle-human-female-5-512.png">
    </head>
    <body>
        <div class="header">
            <p class="header-name">CHANDRAPRIYADHARSHINI</p>
            <p class="header-list">
                <ul class="list-display">
                    <li><a href="#about1" class="header-link">ABOUT</a></li>
                    <li><a href="#education1" class="header-link">EDUCATION</a></li>
                    <li><a href="#skills1" class="header-link">SKILLS</a></li>
                    <li><a href="#profile1" class="header-link">PROFILES</a></li>
                    <li><a href="#contact1" class="header-link">CONTACT</a></li>
                </ul>
            </p>
        </div>

        <div class="about-me">
            <img src="https://cdn.wallpapersafari.com/65/38/eVomt4.jpg" class="about-background-image">
            <div class="my-name">
                <p class="my-name-page">HI, I AM</p>
                <p class="my-name-page1">CHANDRAPRIYADHARSHINI</p>
                <p class="my-name-page2">WEB DEVELOPER</p>
                <a href="resume__.pdf" download class="resume-btn"><b>DOWNLOAD RESUME</b></a>
            </div>
            <button onclick="scrollToTop()" id="topBtn">▲</button>

            <div class="about-me-page" id="about1">
                <p class="about"><b>ABOUT ME</b></p>
                <hr>
                <div class="my-details-content">
                    <div class="details-section">
                        <p><b>I'm Chandrapriyadharshini C, a B.Tech currently studying in Artificial Intelligence and Machine Learning. 
                        I have a strong interest in full stack development and enjoy creating websites. 
                        I'm still learning coding in Python and C, and I like solving problems and communicating ideas clearly.
                         I’m looking for opportunities where I can grow as a developer and learn new things. 
                         In my free time, 
                        I love exploring new websites.
                        </b></p>
                        <p class="content-2"><b>Web development is the process of creating and maintaining websites. 
                        It involves designing the layout, writing clean code, and adding interactive 
                        features that make a website useful and engaging. A web developer works on both the front-end, 
                        which deals with the look and feel of the website, and the back-end, 
                        which handles data, logic, and server communication. Technologies like HTML, 
                        CSS, JavaScript, Python, and various frameworks are commonly used in development. 
                        A well-designed website should be responsive, fast, and user-friendly across different devices. 
                        Web development not only improves technical skills like coding and debugging but also builds creativity, 
                        communication, and problem-solving abilities. It’s a field that constantly evolves, offering something new to learn every day. 
                        Working on web projects helps developers grow both individually and as part of a team, 
                        making it an exciting and rewarding career path in the digital world.
                        </b></p>
                        <hr>
                        <p>Phone no : 9876543210 | email id : priyadharshinibose86@gmail </p>
                    </div>
                    <div class="imge-and-icons">
                        <img src="https://i.pinimg.com/736x/da/6f/1e/da6f1e5d867387420fedf33dfdab74a0.jpg" class="my-image">
                    </div>
                </div>
            </div>

            <div class="education-container" id="education1">
                <p class="title1"><b>EDUCATION</b></p>
                <hr>
                <div class="content-about-education">
                    <div class="content1">
                        <p class="year">2023-2027</p>
                        <p>Bachelor of Technology</p>
                        <p class="university">SAVEETHA ENGINEERING COLLEGE</p>
                        <br>
                        <p class="content2">B.Tech in Artificial Intelligence and Machine Learning is a four-year undergraduate program 
                            that focuses on the study of smart technologies. It combines computer science, machine learning,
                             data science, and deep learning to build intelligent systems. Students learn to design algorithms that allow
                              machines to think, learn, and make decisions. The course includes programming, mathematics, data analysis, and 
                              neural networks. Graduates can work in fields like AI development, data science, robotics, and automation. 
                            This program prepares students for a fast-growing tech industry with high demand for AI professionals.
                        <p>
                    </div>
                </div>
            </div>
        </div>

        <div class="skill-container" id="skills1">
            <p class="skills"><b>SKILLS</b></p>
            <div class="skills-container">
                <div class="skill">
                    <div class="skill-name">HTML</div>
                        <div class="progress-wrapper">
                            <div class="progress-bar-container">
                                <div class="progress-bar" style="width: 68%;"></div>
                            </div>
                        <div class="progress-value">80%</div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">CSS</div>
                        <div class="progress-wrapper">
                            <div class="progress-bar-container">
                                <div class="progress-bar" style="width: 80%;"></div>
                            </div>
                        <div class="progress-value">80%</div>
                    </div>
                </div>
            </div>
            <div class="skills-container">
                <div class="skill">
                    <div class="skill-name">JAVASCRIPT</div>
                        <div class="progress-wrapper">
                            <div class="progress-bar-container">
                                <div class="progress-bar" style="width: 40%;"></div>
                            </div>
                        <div class="progress-value">40%</div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">PYTHON</div>
                        <div class="progress-wrapper">
                            <div class="progress-bar-container">
                                <div class="progress-bar" style="width: 70%;"></div>
                            </div>
                        <div class="progress-value">70%</div>
                    </div>
                </div>
            </div>
            <div class="skills-container">
                <div class="skill">
                    <div class="skill-name">JAVA</div>
                        <div class="progress-wrapper">
                            <div class="progress-bar-container">
                                <div class="progress-bar" style="width: 70%;"></div>
                            </div>
                        <div class="progress-value">70%</div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">SQL</div>
                        <div class="progress-wrapper">
                            <div class="progress-bar-container">
                                <div class="progress-bar" style="width: 70%;"></div>
                            </div>
                        <div class="progress-value">70%</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="profile-container" id="profile1">
        <div class="profile"><b>PROFILES</b></div>
        <hr>
            <div class="github-link">
                <a href="https://github.com/Chandrapriyadharshini" class="hyper-link">GITHUB</a>
                <a href="https://www.linkedin.com/in/chandrapriyadharshini-chandrabose-44327629a/" class="hyper-link">LINKEDIN</a>
            </div>
        </div>

        <p class="contact" id="contact1"><b>CONTACT ME</b></p>
        <div class="contact-container">
            <div class="message">
            <div class="contact-form1">
                <input type="text" placeholder="Name*" required>
                <input type="email" placeholder="Email*" required>
            </div>
            <div class="contact-form2">
                <input type="text" placeholder="Subject">
            </div>
            <div class="contact-form3">
                <input type="text" placeholder="Message" class="input3">
            </div>
            <div class="submit-btn">
                <a href="#" class="submit">Submit</a>
            </div>
            </div>
            <div class="details">
                <p class="subtitles1">Chandrapriyadharshini C</p>
                <p class="subtitles">Web development(fresher)</p>
                <p class="subtitles1">Phone:</p>
                <p class="subtitles">1234567890</p>
                <p class="subtitles1">Email:</p>
                <p class="subtitles">priyadharshinibose86@gmail.com</p>
            </div>
        </div>

        <footer>
            <p>© copyright chandrapriyadharshini. design and developed by themesine</p>
        </footer>
        <script>
            window.onscroll = function() {
                const btn = document.getElementById("topBtn");
                if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                    btn.style.display = "block";
                } else {
                    btn.style.display = "none";
                }
            };
            function scrollToTop() {
                window.scrollTo({ top: 0, behavior: 'smooth' });
            }
        </script>
    </body>
</html>
```
### CSS
```
html {
    scroll-behavior: smooth;
  }
body{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.header{
    background-color: white;
    display: flex;
    width: 100%;
    height: 20%;
    top: 0px;
}
.header-name{
    display: flex;
    padding-left: 10%;
    margin-top: 50px;
    font-size: 25px;
    color: deeppink;
}
.header-list{
    display: flex;
}
.list-display{
    display: flex;
    text-decoration: none;
    list-style-type: none;
    gap: 40px;
    margin-top: 120px;
    font-size: 17px;
    cursor: pointer;
}
li:hover{
    color: blue;
}
.header-link{
    text-decoration: none;
    color: black;
}
.header-link:hover{
    color: blue;
}
.about-me{
    position: relative;
}
.about-background-image{
    width: 1500px;
    height: 650px;
    position: relative;
    top: 30px;
    object-fit: cover;
}
.my-name{
    position: absolute;
    color: white;
}
.resume-btn{
    position: absolute;
    bottom: 130px;
    left: 200px;
    width: 170px;
    background-color:deepskyblue;
    padding: 25px 100px 25px 100px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    font-size: 16px;
}
.resume-btn:hover{
    background-color: dodgerblue;
}
.my-name-page{
    position: absolute;
    width: 500px;
    bottom: 350px;
    left: 200px;
    font-size: 60px;
}
.my-name-page1{
    position: absolute;
    color: white;
    bottom: 250px;
    left: 200px;
    font-size: 60px;
    width: 500px;
}
.my-name-page2{
    position: absolute;
    color: white;
    bottom: 230px;
    left: 200px;
    font-size: 20px;
    width: 500px;
}
.about-me-page{
    margin-top: 50px;
    text-align: center;
    font-size: 25px;
}
.about{
    padding: 40px 40px 30px 40px;
    font-size: 25px;
}
.details-section{
    font-size: 15px;
    width: 600px;
    text-align: left;
    padding-left: 10%;
    margin-top: 4%;
}
.my-details-content{
    display: flex;
}
.content-2{
    color: gray;
}
.my-image{
    width: 450px;
    height: 350px;
    object-fit: cover;
    padding-left: 20%;
    margin-top: 19%;
}
.content-about-education{
    display: flex;
    font-size: 15px;
}
.education-container{
    text-align: center;
    margin-top: 100px;
    background-color: aliceblue;
    padding: 20px;
}
.content1{
    width: 500px;
    margin-left: 33%;
    text-align: left;
}
.year{
    font-size: 20px;
}
.title1{
    font-size: 25px;
}
.content2{
    color: gray;
}
.university{
    font-size: 18px;
}
.skills-container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px 60px;
    max-width: 1000px;
    margin-left: 15%;
    margin-top: 50px;
}
.skills{
    text-align: center;
    margin-top: 50px;
    font-size: 25px;
}
.skill {
    display: flex;
    flex-direction: column;
}
.skill-name {
    color: #555;
    margin-bottom: 8px;
}
.progress-wrapper {
    display: flex;
    align-items: center;
}
.progress-bar-container {
    flex-grow: 1;
    background-color: #e0e6ed;
    height: 8px;
    border-radius: 5px;
    overflow: hidden;
    margin-right: 10px;
}
.progress-bar {
    height: 100%;
    background-color: green;
    border-radius: 5px 0 0 5px;
}
.progress-value {
    color: deeppink;
    font-weight: bold;
    font-size: 14px;
    width: 35px;
    text-align: right;
}
.profile{
    text-align: center;
    font-size: 25px;
    margin-top: 100px;
    margin-bottom: 40px;
}
.github-link{
    display: flex;
    margin-top: 100px;
    margin-left: 20%;
}
.hyper-link{
    text-decoration: none;
    color: black;
    font-size: 18px;
    background-color: whitesmoke;
    padding: 100px 200px 100px 200px;
    border-right: solid 1px black;
    transition: background-color 0.7s ease;
}
.hyper-link:hover{
    background-color: mediumorchid;
    color: white;
}
.contact-container{
    display: flex;
    background-color: aliceblue;
    padding: 50px;
}
.contact-form1{
    margin-left: 15%;
    margin-top: 80px;
    width: 1000px;
}
input{
    text-align: center;
    background-color: white;
    border: none;
    padding: 25px 50px;
}
input:focus{
    outline: none;
    border: none;
}
.contact-form2{
    margin-left: 15%;
    margin-top: 40px;
    width: 1000px;
}
.contact-form3{
    margin-left: 15%;
    margin-top: 50px;
    width: 1000px;
}
.input3{
    padding: 20px 65px 100px 65px;
}
.submit-btn{
    margin-top: 50px;
}
.submit{
    padding: 20px 115px 20px 115px;
    background-color: blue;
    border: none;
    color: white;
    margin-left: 15%;
    cursor: pointer;
    font-size: 20px;
    text-decoration: none;
}
.submit:hover{
    background-color: deepskyblue;
}
.contact{
    text-align: center;
    margin-top: 50px;
    font-size: 25px;
    margin-top: 100px;
    margin-bottom: 50px;
}
.details{
    margin-top: 100px;
    font-size: 18px;
}
.subtitles{
    color: gray;
    margin-top: 30px;
}
.subtitles1{
    margin-top: 30px;
}
footer{
    text-align: center;
    margin-top: 60px;
    font-size: 18px;
    background-color: black;
    color: gray;
    padding: 7px;
}
#topBtn {
    position: fixed;
    bottom: 30px;
    right: 30px;
    padding: 15px 15px;
    background-color: darkblue;
    color: white;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    display: none;
    z-index: 1000;
    font-size: 25px;
  }
  #topBtn:hover {
    background-color: #555;
  }
```
## OUTPUT
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/bdcacc39-c8db-469e-8f5d-5aa58697b6f4" />

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/8352af48-99b9-43a7-a8ea-8dd81d874d79" />

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/b395230c-13f8-4012-8b71-715033639c20" />

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/31366614-41e6-4c8e-b36a-e95f83c56794" />

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/097ed6e7-4849-45fd-8858-c78d89ee986d" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
