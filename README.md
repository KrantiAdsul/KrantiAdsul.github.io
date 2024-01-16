
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Welcome to My Portfolio</title>
</head>
<body>
  <!-- Header -->
  <section id="header">
    <div class="header container">
      <div class="nav-bar">
        <div class="brand">
        <!--  <a href="#hero"><h1><span>M</span>ansi <span>T</span>hanki</h1></a>-->
        <a href="#hero"><h1><span>M</span>[ANSI]<span> C</span>odes</h1></a>
        </div>
        <div class="nav-list">
          <div class="hamburger"><div class="bar"></div></div>
          <ul>
            <li><a href="#hero" data-after="Home">Home</a></li>
            <li><a href="#about" data-after="About">About</a></li>
            <li><a href="#services" data-after="Service">Technical Skillset</a></li>
            <li><a href="#projects" data-after="Projects">Projects</a></li>
            <li><a href="#contact" data-after="Contact">Contact</a></li>
          </ul>
        </div>
      </div>
    </div>
  </section>
  <!-- End Header -->


  <!-- Hero Section  -->
  <section id="hero">
    <div class="hero container">
      <div>
        <h1>Hello, <span></span></h1>
        <h1>My Name is <span></span></h1>
        <h1>Kranti Adsul<span></span></h1>
        <a href="#projects" type="button" class="cta">Portfolio</a>
      </div>
    </div>
  </section>
  <!-- End Hero Section  -->

  <!-- About Section -->
  <section id="about">
    <div class="about container">
      <div class="col-left">
        <div class="about-img">
          <img src="./img/img-3.jpg" alt="img" border=7>
        </div>
      </div>
      <div class="col-right">
        <h1 class="section-title">About <span>me</span></h1>
        <h2>A Data Science Enthusiast, Programmer and Web Developer</h2>
       <p>Hello, my name is <b>Mansi Thanki</b>. I recently graduated with a <b>Master's degree in Computer Science from Northeastern University</b>. During my academic journey, I interned as a Software Engineer at <b>Dassault Systèmes</b>, where I gained valuable industry experience and leveraged technologies like <b>JavaScript, Backbone.js, Java, HTML and CSS</b>. 

         I worked as a <b>Software Engineer for one year at Infogen Labs</b>, India where I worked upon building a training hub for individuals who treat ASD using C#, ASP.NET MVC and JavaScript. I also worked at Shine Infosoft as a Software Engineer where I leveraged technologies like JavaScript, ReactJS, Redux, Tableau, SQL and Python. I am an enthusiastic and ambitious individual who loves to code and come up with innovative ideas! I have good problem solving skills and proficient in <b> JavaScript, Python, Java, C#, C++, SQL and R</b>. Apart from coding, I love to <b>read books, learn new languages</b> and <b>interact with people</b> to create more opportunities. Currently seeking a challenging assignment which will provide avenues for professional learning, hone my technical skills and enrich my experience as well as knowledge in the process. </p>
<!--         <a href="./img/Mansi_Thanki_Resume_SoftwareDeveloper.pdf" class="cta" download>Download Resume</a> -->
        <a href="https://github.com/mansithanki" class="cta">Explore Github</a>
      </div>
    </div>
  </section>
  <!-- End About Section -->

  <!-- Service Section -->
  <section id="services">
    <div class="services container">
      <div class="service-top">
        <h1 class="section-title">Technical<span> Skillset</span></h1>
        <p>I have worked with a wide variety of programming languages. For web applications I use Java and Javascript and finally when I am building prototypes or working on my hobby projects I fall back on Python. Here are a few of the technologies I have worked on:</style></p>
      </div>
      <div class="service-bottom">
        <div class="service-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/services.png"/></div>
          <h2>Programming </h2>
          <h2>Languages</h2>
          <p>JavaScript, Python, Core Java, <br>
             SQL, R, C#</p>
        </div>
        <div class="service-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/services.png"/></div>
          <h2>Web </h2>
          <h2>Technologies</h2>
          <p>ReactJS, HTML, CSS, Bootstrap, AngularJS, Node.js, Selenium, Cypress, Jasmine, Postman </p>
        </div>
        <div class="service-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/services.png"/></div>
          <h2>Cloud</h2>
          <br>
          <p>S3, RDS, EC2, Lambda, CloudFormation, Elastic Beanstalk, AutoScaling, CloudWatch</p>
        </div>
        <div class="service-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/services.png"/></div>
          <h2>Operating System </h2>
          <h2>and Database</h2>
          <p><b>OS: </b>Mac,Windows XP/7/8/10, LINUX</p>
          <p><b>Databases: </b>MySQL, Mongo DB, Oracle Database</p>

        </div>
      </div>
    </div>
  </section>
  <!-- End Service Section -->

  <!-- Projects Section -->
  <section id="projects">
    <div class="projects container">
      <div class="projects-header">
        <h1 class="section-title">Recent <span>Projects</span></h1>
      </div>
      <div class="all-projects">
        <div class="project-item">
          <div class="project-info">
            <h1>DoorDelights – A MERN Food Delivery App</h1>
            <!--<h2>Forensic Investigation on Operating System Logs</h2>-->
            <br>
            <p> Developed a robust food delivery application using MERN stack, Redux, and Git for collaboration; integrated frontend (React.js, Material UI) with backend (Node.js, Express.js, MongoDB) for authentication, orders, and restaurants, enriched with Google APIs for location-based search and a distinctive multi-restaurant purchase feature.<br><b>Tools used:</b> ReactJS, Express.js, Node.js, MongoDB, Redux, MaterialUI</p>
            <a href="https://github.com/hardiknahata/CS5610-DoorDelights-Frontend" class="projbutton">See Project</a>
            <!--             <a href="https://github.com/hardiknahata/CS5610-DoorDelights-Frontend" class="cta">See Project on Github</a> -->
          </div>
          <div class="project-img">
            <img src="./img/img-24.png" alt="img">
          </div>
        </div>

        <div class="project-item">
          <div class="project-info">
            <h1>ImageVoyager - An Image Search App</h1>
            <!--<h2>Forensic Investigation on Operating System Logs</h2>-->
            <br>
            <p> ImageVoyager is a React application for exploring and discovering a wide range of images. It provides a user-friendly interface for searching and viewing images. <br><b>Tools used:</b> Javascript, React.js, Tailwind CSS, Unsplash API</p></p>
            <span><a href="https://github.com/mansithanki/ImageVoyager" class="projbutton">See Project</a>  
            <a href="https://jocular-sprite-109b1d.netlify.app/" class="projbutton">Live Website</a> </span>
          </div>
          <div class="project-img">
            <img src="./img/img-25.png" alt="img">
          </div>
        </div>

         <div class="project-item">
          <div class="project-info">
            <h1>Jobble – A React Native Job Search App</h1>
            <!--<h2>Forensic Investigation on Operating System Logs</h2>-->
            <br>
            <p> A React Native job search app exemplifying sleek UI/UX, real-time API integration (JSearch from RapidAPI), advanced search and pagination, custom API hooks, and adherence to best coding practices. <br><b>Tools used:</b> ReactJS, Express.js, Node.js, MongoDB, Redux, MaterialUI</p>
            <a href="https://github.com/mansithanki/react_native_job_app" class="projbutton">See Project</a>  
          </div>
          <div class="project-img">
            <img src="./img/img-23.png" alt="img">
          </div>
        </div>
        
        <div class="project-item">
          <div class="project-info">
            <h1>USA Accidents Severity Prediction and EDA</h1>
            <!--<h2>Forensic Investigation on Operating System Logs</h2>-->
            <br>
            <p> Analyzed US Accidents dataset, conducted EDA, & developed a severity prediction model. 
Performed Random forest & logistic regression along with hyperparameter tuning & undersampling techniques.
Achieved 85% accuracy & 79% recall with logistic regression, and 93% accuracy and 83% recall with random forest.<br><b>Tools used:</b> R and Python</p>
          <a href="https://github.com/mansithanki/USA_Accidents_EDA_and_SeverityPrediction_IDMP_Project" class="projbutton">See Project</a> 
          </div>
          <div class="project-img">
            <img src="./img/img-22.png" alt="img">
          </div>
        </div>
        
        <div class="project-item">
          <div class="project-info">
            <h1>Full Stack Amazon Clone App using ReactJS</h1>
            <!--<h2>Forensic Investigation on Operating System Logs</h2>-->
            <br>
            <p> Developed Amazon Clone App using ReactJS, HTML, CSS, React Context API, Node.js & VSCode. Designed Front-end using MaterialUI & used Google Firebase for Authentication, Database & Hosting.<br><b>Tools used:</b> JavaScript, ReactJS, MaterialUI</p>
            <a href="https://github.com/mansithanki/Amazon-Clone-Application" class="projbutton">See Project</a> 
          
          </div>
          <div class="project-img">
            <img src="./img/img-21.png" alt="img">
          </div>
        </div>
        
         <div class="project-item">
          <div class="project-info">
            <h1>Dungeons and Dragons - A Java MVC game</h1>
            <!--<h2>Forensic Investigation on Operating System Logs</h2>-->
            <br>
            <p> Implemented a dungeon game using JAVA and object-oriented design principles. Developed GUI using Swing and performed JUnit tests. Applied SOLID principles & used MVC Design Pattern.<br><b>Tools used:</b> Java, Swing</p>
          </div>
          <div class="project-img">
            <img src="./img/img-20.png" alt="img">
          </div>
        </div>
        
        <div class="project-item">
          <div class="project-info">
            <h1>Forensic Investigation on Operating System Logs</h1>
            <!--<h2>Forensic Investigation on Operating System Logs</h2>-->
            <br>
            <p>Developed a tool for Cyber Forensic Experts to detect tampering of OS logs using cryptographic hashes,
              Anomaly detection using timestamp-based method and Event correlation using semantic rule-based method.<br><b>Tools used:</b> C# .NET</p>
          </div>
          <div class="project-img">
            <img src="./img/img-6.JPG" alt="img">
          </div>
        </div>
        <div class="project-item">
          <div class="project-info">
           <!-- <h1>Realtime Corona Virus Outbreak Notification System</h1>-->
            <h1>Realtime Corona Virus Outbreak Notification System</h1>
            <br>
            <p>Developed a Python notification application to provide the realtime COVID-19 data to the user by performing
              web scrapping on MoHFW India.
              <br><b>Tools Used:</b> Visual Studio Code, Beautiful Soup, Plyer, Tkinter</p>
          </div>
          <div class="project-img">
            <img src="./img/img-7.jpg" alt="img">
          </div>
        </div>
        <div class="project-item">
          <div class="project-info">
            <h1>Customer Relationship Management App</h1>
            <br>
            <!--<h2>Coding is Love</h2>-->
            <p>A fully functional progressive web app (PWA) deployed in cloud to help manage and analyze customer data. <br> Tools Used: IntelliJ IDEA, Spring Boot, Vaadin, Spring Data, Spring Security</p>
          </div>
          <div class="project-img">
            <img src="./img/img-8.JPG" alt="img">
          </div>
        </div>
        <div class="project-item">
          <div class="project-info">
            <h1>Road Sign Recognition using CNN</h1>
            <!--<h2>Coding is Love</h2>-->
            <p>Used Convolutional Neural networks and python libraries to classify road signs present in the images into
              different categories which is useful for autonomous vehicles. Accuracy achieved by this model is 95%.
              <br><b>Libraries used:</b>TensorFlow, Keras, PIL, Matplotlib, Sklearn, Pandas, Numpy. 
              <br><b>Tools:</b> Jupyter, Tkinter</p>
          </div>
          <div class="project-img">
            <img src="./img/img-10.JPG" alt="img">
          </div>
        </div>
        <div class="project-item">
          <div class="project-info">
            <h1>Personality Prediction System</h1>
            <!--<h2>Coding is Love</h2>-->
            <p>Built ML model for classifying persons based on their characteristics and finding group of people with similar
              characteristic from dataset using logistic regression, decision trees, K-means clustering in Python.<br>
              Used data mining concepts like missing value handling, Normalization, discretization while exploring data.
              <br><b>Libraries used:</b> Pandas, NumPy & Sci-kit learn.<br> <b>Tool Used:</b> RStudio, Selenium </p>
          </div>
          <div class="project-img">
            <img src="./img/img-11.jpg" alt="img">
          </div>
        </div>
        <div class="project-item">
          <div class="project-info">
            <h1>Smart Washroom</h1>
            <!--<h2>Coding is Love</h2>-->
            <p>An IOT based project to provide an eco-friendly and cost-effective alternative to auto-flushing technology in
              India which was implemented for only Rs 930.<br><b>Tools Used :</b> Arduino IDE, Arduino Nano <br><b>Sensors Used:</b> Proximity Sensors, Magnetic Door Switch, Soil Moisture Sensor, Buzzer, LED</p>
          </div>
          <div class="project-img">
            <img src="./img/img-5.JPG" alt="img">
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Projects Section -->

 

  <!-- Contact Section -->
  <section id="contact">
    <div class="contact container">
      <div><h1 class="section-title">Contact <span>info</span></h1></div>
      <div class="contact-items">
        <div class="contact-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/phone.png"/></div>
          <div class="contact-info">
            <h1>Phone</h1>
            <h2>+1 617-606-0924</h2>
          </div>
        </div>
        <div class="contact-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/new-post.png"/></div>
          <div class="contact-info">
            <h1>Email</h1>
            <h2>thankimansi0202@gmail.com</h2>
            <h2>thanki.m@northeastern.edu</h2>
            <!--<h2>abcd@gmail.com</h2>-->
          </div>
        </div>
        <div class="contact-item">
          <div class="icon"><img src="https://img.icons8.com/bubbles/100/000000/map-marker.png"/></div>
          <div class="contact-info">
            <h1>Address</h1>
            <h2>San Jose, CA, USA</h2>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Contact Section -->

  <!-- Footer -->
  <section id="footer">
    <div class="footer container">
      <div class="brand"><h1>Mansi Thanki</h1></div>
      <h2>Get in touch and Hire Me!</h2>
      <div class="social-icon">
        <div class="social-item">
          <a href="https://www.facebook.com/mansi.thanki.37/"><img src="https://img.icons8.com/bubbles/100/000000/facebook-new.png"/></a>
        </div>
        <div class="social-item">
          <a href="https://www.instagram.com/thanki_mansi/"><img src="https://img.icons8.com/bubbles/100/000000/instagram-new.png"/></a>
        </div>
        <div class="social-item">
          <a href="https://twitter.com/thanki_mansi"><img src="https://img.icons8.com/bubbles/100/000000/twitter.png"/></a>
        </div>
        <div class="social-item">
          <a href="https://www.linkedin.com/in/mansi-thanki-15721018a"><img src="https://img.icons8.com/bubbles/100/000000/linkedin.png"/></a>
        </div>
      </div>
      <p>Copyright © 2022 Mansi Thanki. All rights reserved</p>
    </div>
  </section>
  <!-- End Footer -->
  <script src="./app.js"></script>
</body>
</html>
