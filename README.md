# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
### index.html
```
index.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(wallpaper\ for\ intel\ 1.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 90%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #6fa1f8;
                font-size: 35px;
                font-weight: 700;
                margin-left: -100px;
                letter-spacing: 3px;
            }
            img{
                height:70px;
                margin-top:-3px;
                margin-left:5px;
                margin-right:5px;
            }
            span {
                color: white;
            }
            
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 52%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color:#6fa1f8;
                font-weight: 700;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text h3 {
                color:#6fa1f8;
                font-weight: 700;
                font-size: 45px;
                letter-spacing: 3px;
            }
            .text p {
                color:white;
                text-transform: capitalize;
                font-size: 24px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 4px -20px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 50px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color:white;
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <img src="logo.jpeg">
            <h1 class="logo">Intel<sup>&reg</sup><span>vPRO</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/members.html"> Members </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        
        </div>
        <div class="content">
            <div class="text">
                <h2 class="logo">INTEL<h2>
                <h3 class="logo">CORE PROCESSOR</h3>
                <br>
                <p>Welcome to a new level of creating, gaming, and productivity with more power, performance, and efficiency for every computing need</p>
                <br>
                <div>
                    <a href="#" class="login">LOG IN</a>
                    <a href="#" class="signup">SIGN UP</a>
                </div>
                
                
            </div>
        </div>  
    </div>
    <footer>
        <center>DESIGNED AND DEVELOPED BY NARASIMHAN S(212223230133)</center>
    </footer>
</body>
</html>
```
### products.html
```
product.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Product Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(227, 147, 194, 0.75),rgba(232, 150, 199, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-product {
                border: 1px;
                padding: 10px;
                color: gray;
                background-color:#f775db;
                border-radius: 30px;
            }
            .logo {
                color:#f775db;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: gray;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: hsla(0, 3%, 77%, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: gray;
            } 
            ::placeholder {
                color: gray;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: gray;
                border-radius: 10px;
                background:#f775db;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: gray;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: gray;
                background-color:#f775db;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: gray;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid gray;
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 70px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color:#f775db;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: gray;
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color:#f775db;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">DataNerd</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/homepage.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/products.html" class="bg-product"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/members.html"> Members </a></li>
                <li><a href="http://127.0.0.1:8000/static/contactus.html"> Contact us</a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
              
                
                <div class="box">
                    <h3> Fusion Time </h3>
                    <p> Plot high-performance time-series visualizations. </p>
                </div>
                <div class="box">
                    <h3> Yellowfin BI and Analytics </h3>
                    <p> Powerful and flexible embedded analytics platform. </p>
                </div>
                <div class="box">
                    <h3> WebFlow Pro Studio </h3>
                    <p> Rapid low-code app creation. </p>
                </div>
                <div class="box">
                    <h3> Fusion Grid </h3>
                    <p> Rocket fuel for data intensive applications with integrated charting. </p>
                </div>
                <div class="box">
                    <h3> WebScale Pro Manager </h3>
                    <p> Seamless high-traffic handling. </p>
                </div>
                

            </div>
              
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by NARASIMHAN S (212223230133) </center>
    </footer>
</body>
</html>
```

### members
```
people.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Software Development Company</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(wallpaper\ for\ intel\ 1.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 90%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            
            .logo {
                color: #6fa1f8;
                font-size: 35px;
                font-weight: 700;
                margin-left: -100px;
                letter-spacing: 3px;
            }
            img{
                height:50px;
                margin-top:-3px;
                margin-left:-5px;
                margin-right:5px;
            }
            span {
                color: white;
            }
            
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 150px;
                
                background: transparent;
            }
            .image table {
                border: 0;
                color: white;
                position: relative;
                left: 200px;
                
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid white;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: #00d5ff;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <img src="logo.jpeg">
            <h1 class="logo">Intel<sup>&reg</sup><span>vPRO</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/index.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/members.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="Eren Yeager.jpeg"> </td>
                    <td> <img src="MIKASA.jpeg"> </td>
                    <td> <img src="Levi.jpeg"> </td>
                    <td> <img src="3f55fdc0-6564-47cb-9c55-079c317af60b.jpeg"> </td>
                    <td> <img src="gojo.jpeg"> </td>
                    <td> <img src="Yuji Itadori.jpeg"> </td>
                    
                <tr align="center">
                    <th> EREN YEAGER</th>
                    <th> MIKASA</th>
                    <th> LEVI</th>
                    <th> SUKUNA</th>
                    <th> GOJO SATORU</th>
                    <th> YUJI ITADORI</th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO CO-FOUNDER </td>
                    <td> CTO CO-FOUNDER </td>
                    <td> DIRECTOR </td>
                    <td> Ass.DIRECTOR </td>
                    <td> Dy.DIRECTOR </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center>DESIGNED AND DEVELOPED BY NARASIMHAN S(212223230133) </center>
    </footer>
</body>
</html>
```

### contact.html
```
contact.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(wallpaper\ for\ intel\ 1.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 90%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #6fa1f8;
                font-size: 35px;
                font-weight: 700;
                margin-left: -100px;
                letter-spacing: 3px;
            }
            img{
                height:70px;
                margin-top:-3px;
                margin-left:5px;
                margin-right:5px;
            }
            span {
                color: white;
            }
            
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 20px;
                background: transparent;
                position: relative;
                top: 80px;
            }
            .box-1 {
                height: 330px;
                width: 430px;
                border: 3px solid white;
                border-radius: 50px;
                background: transparent;
                position: relative;
                top: 50px;
                left: 250px;
            }
            .box-2 {
                height: 330px;
                top: 50px;
                width: 430px;
                border: 3px solid white;
                border-radius: 50px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color:white;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid white;
                border-radius: 10px;
                padding: 15px 20px;
                font-size: 15px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                display: flex;
                color: white;
                padding: 5px 10px;
                position: relative;
                top: 30px;
                left: 41px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 5px 30px;
                left: 30px;
                color: white;
                border-radius: 50px;
                background: #6fa1f8;
                cursor: pointer;
                position: relative;
                top: 30px;
            }
            box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: white;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color: #6fa1f8;
                font-size: 20px;
            }
            footer {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <img src="logo.jpeg">
            <h1 class="logo">Intel<sup>&reg</sup><span>vPRO</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/members.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="2" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
        <div class="box-2"> 
            <h2> Contact Information </h2>
            <p> <span>Address</span> : Tidel park No.4, Rajiv Gandhi Salai, Taramani, Chennai</p>
            <p> <span>Email</span> : anubharathi2005@gmail.com</p>
            <p> <span>Phone</span> : 8428469210</p>
            <p> <span>SubCategory</span> : Subsidiary of Foreign company</p>
        </div>
    </div>
</div>
<footer>
    <center>DESIGNED AND DEVELOPED BY NARASIMHAN S(212223230133) </center>
</footer>
</body>
```
## OUTPUT:
### index.html
![Screenshot 2024-04-28 141615](https://github.com/Narasimhan05/softweb/assets/132819871/e21e15cd-e052-4a00-884a-fb87845d7548)

### products.html
![Screenshot 2024-04-28 141706](https://github.com/Narasimhan05/softweb/assets/132819871/c97c9a98-e80b-4ce2-a080-6389191b7b23)

### members.html
![Screenshot 2024-04-28 141916](https://github.com/Narasimhan05/softweb/assets/132819871/036788dd-869e-4f0c-9533-6a628c7e6b23)

### contact.html
![Screenshot 2024-04-28 141943](https://github.com/Narasimhan05/softweb/assets/132819871/9f5fe473-72c5-407f-bdc7-db48b34c6057)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
