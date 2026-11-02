# CSS-.Lecture
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body><div class="FULL STACK DELEOPEMENT COURSE">
        <h1>FULL STACK DEVELOPEMENT COURSE</h1>
        <hr>
</div> <br>
    <div class="full-stack">
        <h1>FULL STACK DEVELOPEMENT COURSE 2</h1>
        <hr>
    </div>
    <section>
    <b>Bold</b>
    <strong>Strong</strong>
    <i>Italic</i>
    <em>Italic</em>
    <mark>Mark tag</mark>
    <del>Delete</del> <samp> : Undo</samp>
    <ins>Underline</ins>
    </section>
     <section class="course-info">
        <h1>COURSES</h1>
        <ol>
            <li>MATHEMATICS</li>
            <li>HINDI</li>
            <li>ENGLISH</li>
            <li>COMPUTER</li>
        </ol>
     </section>
    <section class="admin-info">
        <h1>ADMISSION PROCESS</h1>
        <ol>
            <li>ATTEND THE INTERVIEW</li>
            <li>COMPLETE THE ADMISSION</li>
        </ol>
    </section>
    <section class="subject-info">
        <h1>SUBJECT INFORMATION</h1>
        <dl>
            <dt>Mathematics</dt>
            <dd>Learn numbers,calculation and problem solving</dd>
            <dt>Computer</dt>
            <dd>Learn programming,software and technology</dd>
        </dl>
    </section>
    <div class="contect-info">
        <h1>CONTECT INFORMATION</h1>
        <p>Contact :7983786228</p>
        <p>Email : indermohanluthra97752@gmail.com</p>
        
    </div>
    <div class="frame">
<a href="https://www.google.com">Visit Google</a>
    <p>H<sub>2</sub>O</p>
    <p>x<sup>2</sup></p>
    <nav>
        <p><a href="index.html">Home</a></p>
        <p><a href="about.html">About</a></p>
        <p><a href="services.html">Services</a></p>
        <p><a href="contact.html">Contact</a></p>
        <p><a href="https://timely-heliotrope-2ba672.netlify.app/">Movieshub24x7</a></p>
        <p><a href="https://calfare.netlify.app/">Calfare</a></p>
    </nav>
    <table border="1">
        <thead>
          <tr>
            <th>Sr No</th>
            <th>Name</th>
            <th>Roll No</th>
            <th>Email</th>
            <th>Phone</th>
            <th>Web Development</th>
            <th>Physics</th>
            <th>Chemistry</th>
            <th>Maths</th>
            <th>Total</th>
            
          </tr>
          <tr>
            <tdcolspan="3">Students Information</td>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1.</td>
            <td>Rohit</td>
            <td>042</td>
            <td>rohit@gmail.com</td>
            <td>9795893226</td>           
            <td>85</td>
            <td>90</td>
            <td>100</td>
            <td>88</td>
            <td>361</td>
          </tr>
          <tr>
            <td>2.</td>
            <td>Ramesh</td>
            <td>043</td>
            <td>ramesh@gmail.com</td>
            <td>9722546387</td>
            <td>80</td>
            <td>66</td>
            <td>97</td>
            <td>82</td>
            <td>325</td>
          </tr>
          <tr>
            <td>3.</td>
            <td>Suresh</td>
            <td>044</td>
            <td>suresh@gmail.com</td>
            <td>9753889248</td>           
            <td>88</td>
            <td>70</td>          
            <td>56</td>
            <td>88</td>
            <td>322</td>
          </tr>
          <tr>
            <td>4.</td>
            <td>Mahesh</td>
            <td>045</td>
            <td>mahesh@gmail.com</td>
            <td>9753889249</td>
            <td>85</td>
            <td>90</td>
            <td>100</td>
            <td>67</td>
            <td>342</td>
          </tr>
        </tbody>
    </table>


    <div>
        <h2>Student Info</h2>
        <form>
            <label>Student Name</label>
            <input type="text" placeholder="Enter a name" value=""
            id="StudentName"
            Minlenrth="3"
            Maxlength="50"
            />
            <label>Mobile:</label>
            <input type="tel"
            placeholder="Enter a mobile number"
            id="Mobile"
            />
            <label>Email id</label>
            <input type="email"
            placeholder="Enter Email id"
            value=""
            id="email id"
            />
            <label>Password</label>
            <input type="password"
            minlength="10"
            maxlength="15"
            placeholder="Enter Password"
            id="password"
            />
            <label for="otp">OTP</label>
          <input
            id="otp"
            type="text"
            name="otp"
            inputmode="numeric"
            placeholder="Enter OTP"
            maxlength="6"
            pattern="[0-9]{6}"
            >
            <label>Upload PDF</label>
            <input type="file"/>

            <label>Gender</label>
            <input type="radio" id="gender" name="gender" value="gender" />Male
            <input type="radio" id="gender" name="gender" value="gender" />Female
            <button type="submit">Submit</button>
        </form>
    </div>
    <div
        
        style="background-color: red;
        height: 100px;
        width: 100px;
        padding: 10px;
        border: 2px solid black;
      
        margin-top: 20px;
        "
        class="square"
        >
        100 X 100
        </div>
        <div style="border-top:2px solid red;
        width: 100px;
        height:100px;
        margin-top: 20px;
        border-left: 2px solid blue;
        border-right: 2px solid greenyellow;
        border-bottom: 2px solid orange;
        background-color :rgb(88, 15, 117);
        " class="border">
    </div>
    </div>
    <div></div>
    <button><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-airplane-fill" viewBox="0 0 16 16">
  <path d="M6.428 1.151C6.708.591 7.213 0 8 0s1.292.592 1.572 1.151C9.861 1.73 10 2.431 10 3v3.691l5.17 2.585a1.5 1.5 0 0 1 .83 1.342V12a.5.5 0 0 1-.582.493l-5.507-.918-.375 2.253 1.318 1.318A.5.5 0 0 1 10.5 16h-5a.5.5 0 0 1-.354-.854l1.319-1.318-.376-2.253-5.507.918A.5.5 0 0 1 0 12v-1.382a1.5 1.5 0 0 1 .83-1.342L6 6.691V3c0-.568.14-1.271.428-1.849"/>
</svg></button>
<button><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-amazon" viewBox="0 0 16 16">
  <path d="M10.813 11.968c.157.083.36.074.5-.05l.005.005a90 90 0 0 1 1.623-1.405c.173-.143.143-.372.006-.563l-.125-.17c-.345-.465-.673-.906-.673-1.791v-3.3l.001-.335c.008-1.265.014-2.421-.933-3.305C10.404.274 9.06 0 8.03 0 6.017 0 3.77.75 3.296 3.24c-.047.264.143.404.316.443l2.054.22c.19-.009.33-.196.366-.387.176-.857.896-1.271 1.703-1.271.435 0 .929.16 1.188.55.264.39.26.91.257 1.376v.432q-.3.033-.621.065c-1.113.114-2.397.246-3.36.67C3.873 5.91 2.94 7.08 2.94 8.798c0 2.2 1.387 3.298 3.168 3.298 1.506 0 2.328-.354 3.489-1.54l.167.246c.274.405.456.675 1.047 1.166ZM6.03 8.431C6.03 6.627 7.647 6.3 9.177 6.3v.57c.001.776.002 1.434-.396 2.133-.336.595-.87.961-1.465.961-.812 0-1.286-.619-1.286-1.533M.435 12.174c2.629 1.603 6.698 4.084 13.183.997.28-.116.475.078.199.431C13.538 13.96 11.312 16 7.57 16 3.832 16 .968 13.446.094 12.386c-.24-.275.036-.4.199-.299z"/>
  <path d="M13.828 11.943c.567-.07 1.468-.027 1.645.204.135.176-.004.966-.233 1.533-.23.563-.572.961-.762 1.115s-.333.094-.23-.137c.105-.23.684-1.663.455-1.963-.213-.278-1.177-.177-1.625-.13l-.09.009q-.142.013-.233.024c-.193.021-.245.027-.274-.032-.074-.209.779-.556 1.347-.623"/>
</svg></button>
<h1>Font Awesome icon library</h1>

<p>Some Font Awesome icons:</p>
<i class="fas fa-cloud"></i>
<i class="fas fa-heart"></i>
<i class="fas fa-car"></i>
<i class="fas fa-file"></i>
<i class="fas fa-bars"></i>

<p>Styled Font Awesome icons (size and color):</p>
<i class="fas fa-cloud" style="font-size:24px;"></i>
<i class="fas fa-cloud" style="font-size:36px;"></i>
<i class="fas fa-cloud" style="font-size:48px;color:red;"></i>
<i class="fas fa-cloud" style="font-size:60px;color:lightblue;"></i>

<h2><ul style="width:300px;height:400px;border:2px solid red;background-color: 3px solid blue;margin-top: 40px;margin-left: 100px;"
div.static{
    position:static;border:3px solid indigo;
}>
    <li>6 items background width height margin padding</li>
    <li>6 items background width height margin padding</li>
    <li>6 items background width height margin padding</li>
    <li>6 items background width height margin padding</li>
    <li>6 items background width height margin padding</li>
    <li>6 items background width height margin padding</li>
</ul></h2>
<img src="https://rukminim2.flixcart.com/fk-p-flap/3140/700/image/ea6fe515dd7caa68.png?q=60"
width="800px"
height="650">



    <link rel = stylesheet href="style.css">
</body>
</html>
