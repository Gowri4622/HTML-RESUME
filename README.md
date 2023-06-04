### EX NO: 03

# <p align="center">Web Portfolio using HTML & CSS</P>

## Aim:
To create a web portfolio/cv by using html & css.

## Algorithm:

Step 1: Create a folder and index.html

Step 2: Write the code for both html and css

Step 3: Connect the css into html by the syntax

Step 4: Create the folder images and give the correct path

Step 5: Run the program.


## Program

### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Resume</title>
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
   
<div id="page">
    <div class="photo-and-name">
        <img src="assets/image/profile.png"  class="photo" alt="Profile Picture">
        <div class="contact-info-box">
            <h1 class="name">Gowri M</h1>
            <br>
            <h3 class="job-title">Innovator | Problem Solver | Quick Learner</h3>
            <p class="contact-details"><img src="assets/image/mail.png" width="20" height="20" ">Email : gowri.manimaran.2002@gmail.com &nbsp;    &nbsp;<img src="assets/image/phone.png" width="20"; height="20" ">Phone : 8925757455</p>
            
        </div>
    </div>
    <div id="objective">
        <h3>Objective</h3>
        <p>
            To take a challenging and managerial role in the field of Computer programming and implement the expertise and experience gained in this field to develop complex project with efficiency and quality. 
        </p>
    </div>
    <div id="education">
        <h3>Education</h3>
        <table>
            <tr class="school-1">
                <td rowspan="2">2020 - 2024</td>
                <td><b>Saveetha Engineering College</b></td>
            </tr>
            <tr class="school-2">
                <td>3rd year - CGPA : 9.21</td>
            </tr>
            
            <tr class="school-1">
                <td rowspan="2">2019 - 2020</td>
                <td><b>Sir Ramaswami HR SEC School</b></td>
            </tr>
            <tr class="school-2">
                <td>12th - 71.8%</td>
            </tr>
            
            <tr class="school-1">
                <td rowspan="2">2017 - 2018</td>
                <td><b>Britannia High School</b></td>
            </tr>
            <tr class="school-2">
                <td>10th - 87.2%</td>
            </tr>
        </table>
    </div>
    <div id="skills">
        <h3>Skills</h3>
    </div>
        <div class="container">
            <ul class="myUL" style="line-height: 280%;">
                <li>Programming languages - C, Python, HTML, CSS, Java</li>
                <li>Mobile App Development</li>
                <li>Solid knowledge of Web Technology</li>
                <li>Practical knowledge of Machine Learning</li>
                <li>Interpersonal communication skill and Teamwork</li>
              </ul>
        </div>
        
    <div id="project">
        <h3>Projects</h3>
        <div class="projects">
        <h4>1 . The Women Safety Android App</h4>
        <p>This app was build with the help of Java and XML in Android Studio.tracking the GPS
            location constantly and adding emergency numbers along with concise location through
            one-touch alert message service and can also be can be triggered just by shaking the
            android device in which the app is installed.</p>
        </div>
        <div class="projects">
            <h4>2 . Emotion Based Music Recommendation</h4>
            <p>The project emotion based music built by using mediapipe and keras. Also opencv and
                streamlit is used to create a webapp for capturing the webcam in the browser with the
                use of streamlit-webrtc module.</p>
        </div>
        <div class="projects">
            <h4>3 . Digitizing Handwritten Data</h4>
            <p>It was done with the help of Convolutional deep neural network and Deep
                learning. Build a convolutional neural network model that is able to classify to it's
                appropriate numerical value.
                </p>
        </div>
    </div>
    <div id="education">
        <h3>Certifications</h3>
        <table>
            <tr class="school-1">
                <td rowspan="2">March 2021</td>
                <td><b>Certification of Completion in Java Programming</b></td>
            </tr>
            <tr class="school-2">
                <td>GreatLearning</td>
            </tr>
            
            <tr class="school-1">
                <td rowspan="2">September 2021</td>
                <td><b>Certification of Completion in Django</b></td>
            </tr>
            <tr class="school-2">
                <td>Udemy</td>
            </tr>
            
            <tr class="school-1">
                <td rowspan="2">February 2022</td>
                <td><b>Certification of Assessment in SQL</b></td>
            </tr>
            <tr class="school-2">
                <td>HackerRank</td>
            </tr>
            <tr class="school-1">
                <td rowspan="2">May 2022</td>
                <td><b>Certification of Completion in Deep Learning</b></td>
            </tr>
            <tr class="school-2">
                <td>Infosys</td>
            </tr>
        </table>
        
    </div>
    <div id="skills">
        <h3>Area of Interests</h3>
    </div>
        <div class="container">
            <ul class="myUL" style="line-height: 280%; list-style-type: circle;" >
                <li>Debugging errors</li>
                <li>Learning languages</li>
                <li>Travel</li>
                <li>Listening music</li>
              </ul>
        </div>
        <div id="objective">
            <h3>declaration</h3>
            <p>
                I hereby declare that all the details provided above are true to the best of my knowledge. I hereby confirm that all the facts stated above are accurate to the best of my belief.
            </p>
        </div>
    
</div>

</body>
</html>


```

### style.css
```css
* {margin: 0;padding: 0;}

body{font-family: 'Montserrat', sans-serif;}

#page {
    min-height: 200px;
    width: 60%;
    min-width: 600px;
    background: #faf3f5;
    margin: 50px auto;
    padding: 30px;
    color: #d64161;
    border-color: #000;
    border-style: double;
}



.photo {
    width: 15%;
    min-width: 130px;
    float: left;
    border-color: #d64161;
    margin-right: 20px;
}

.contact-info-box {
    width: 70.9%;
    display: inline-block;
}

.name {
    margin-bottom: -5px;
}
.job-title {
    display: inline-block;
}

.contact-details {
    background: #f0859c;
    color: white;
    text-align: center;
    margin: auto;
    margin-top: 25px;
    padding: 5px;
    font-size: 15px;
}
.container {
    padding-left: 150px;
  }
  .projects {
    padding-left: 150px;
    color: #000;
    line-height: 200%;
  }

  
ul.myUL {
    display: inline-block;
    text-align: left;
    color: #000;
  }

.gh{
    align-items: center;
    padding-right: 0;
}



#objective h3 {
    border: 1px solid #d3d3d3;
    border-color: #960726;
    text-transform: uppercase;
    padding: 5px;
    border-radius: 5px;
    margin: 30px 0 10px;
}

#objective p {
    padding: 0 5px;
    line-height: 25px;
    font-size: 14px;
    color: #000;
}

#education h3 {
    border: 1px solid #d3d3d3;
    border-color: #960726;
    text-transform: uppercase;
    padding: 5px;
    border-radius: 5px;
    margin: 30px 0 10px;
}

#education table td {
    padding: 5px;
    font-size: 14px;
    color: #000;
}

#education table tr.school-1 td:first-child {
    width: 120px;
    color: gray;
    padding-bottom: 25px;
}

#education table tr.school-2 td:first-child {
    padding-bottom: 25px;
}

#skills h3 {
    border: 1px solid #d3d3d3;
    border-color: #960726;
    text-transform: uppercase;
    padding: 5px;
    border-radius: 5px;
    margin: 30px 0 10px;
}

#skills table td {
    padding: 5px;
    font-size: 14px;
    color: #000;
}

#skills table tr.work-1 td:first-child {
    width: 120px;
    color: gray;
    padding-bottom: 25px;
}

#skills table tr.work-1 td {
    padding-bottom: 25px;
}

#skills table tr.work-2 td:first-child {
    width: 120px;
    color: gray;
}

#project h3 {
    border: 1px solid #d3d3d3;
    border-color: #960726;
    text-transform: uppercase;
    padding: 5px;
    border-radius: 5px;
    margin: 30px 0 10px;
}

#project table td {
    padding: 8px;
    font-size: 15px;
    color: #000;
}

#project table tr td:first-child {
    width: 200px;
}

#project table tr td:nth-child(2) {
    width: 300px;
}


```

## Output

![Screenshot 2023-06-04 113714](https://github.com/Gowri4622/html-resume/assets/75235455/bef07e35-fb52-4022-bf3a-8e580fa5f958)
![Screenshot 2023-06-04 113726](https://github.com/Gowri4622/html-resume/assets/75235455/ae03f867-9c70-481f-a4b1-de2b36c69121)
![Screenshot 2023-06-04 113739](https://github.com/Gowri4622/html-resume/assets/75235455/ded5ebcf-daa2-476a-8a79-b0994ec49227)



## Result
Thus, the web portfolio/cv is developed successfully using HTML & CSS.
