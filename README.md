# E-Commerce-website
this website contain home page,login page and contact us page which is directly connected through database mysql using nodejs
# code for final web page
<!DOCTYPE html>
<html>

<head>
    <title></title>
    <link rel="stylesheet" type="text/css" href="assets/style1.css">
</head>

<body>
    <header>
        <nav>
            <div class="logo">
                <h1 class="animate infinite bounce"> BEST E-COMMERCE WEBSITE</h1>
            </div>
            <div class="menu">
                <a href="#">HOME</a>
                <a href="index.html">LOGIN</a>

                <a href="contact.html">CONTACT</a>
            </div>
        </nav>
        <main>
            <section>
                <h3>WELCOME </h3>
                <h1>BEST PRICE AND BEST QUALITY <span></span></h1>
                <p>ONLY AVAILABLE ON THIS SITE</p>
                <a href="#" class="btnone">LEARN MORE</a>
                <a href="#" class="btntwo">SIGN up</a>
            </section>







    </header>
</body>

</html>
  # style of web page
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('../images/back.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}

nav {
    width: 100%;
    height: 15vh;
    background: rgba(0, 0, 0, 0.4);
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-transform: uppercase;
}

nav .logo {
    width: 25%;
    text-align: center;
}

nav .menu {
    width: 40%;
    font-size: large;
    background: none;
    display: flex;
    justify-content: space-around;
}

nav .menu a {
    width: 25%;
    text-decoration: none;
    color: white;
    font-weight: bold;
}

main {
    width: 100%;
    height: 85vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

section {}

section h3 {
    font-size: 80px;
    font-weight: 900;
    letter-spacing: 3px;
    text-shadow: 1px 1px 2px black;
    color: white;
}

section h1 {
    /* margin: 30px 0 20px 0; */
    font-size: 55px;
    font-weight: 700;
    text-shadow: 2px 1px 5px black;
    text-transform: uppercase;
    color: white;
}

section p {
    font-size: 45px;
    font-weight: bold;
    word-spacing: 2px;
    margin-bottom: 25px;
    text-shadow: 1px 1px 1px black;
    text-transform: uppercase;
    color: white;
}

section a {
    padding: 12px 30px;
    border-radius: 4px;
    outline: none;
    text-transform: uppercase;
    font-size: 20px;
    font-weight: 500;
    text-decoration: none;
    letter-spacing: 1px;
    word-spacing: 2px;
}

section .btnone {
    background: white;
    font-weight: 100;
    color: #000;
}

section .btntwo {
    background: white;
    font-weight: 100;
    color: #000;
}
  
  #code for login page
  
  <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=devive-width,initial-scale=1.0">
    <title>login UI</title>
    <link rel="stylesheet" href="assets/style.css">

</head>

<body>
    <section class="box">
        <div class="design">
            <div></div>
            <div></div>
            <div></div>
            <div></div>
        </div>
        <div class="form">
            <h2> user login</h2>
            <form action="" method="POST">
                <input type="email" name="username" class="input-field" placeholder="username" />
                <input type="password" name="password" class="input-field" placeholder="password" />
                <input type="button" class="btn" value="LOGIN">
            </form>
        </div>
    </section>
</body>

</html>
 ** #style of login page**
  . {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
    outline: none;
    border: none;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: linear-gradient(-45deg, #7f379b, #ffa26c);
}

.box {
    width: 900px;
    height: 400;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #fff;
    box-shadow: 0 0 15px #000000;
    border-radius: 15px;
    overflow: hidden;
}
  
  
  
  # code of contact us page
  
  
  <!DOCTYPE html>
<html>

<head>
    <title>contact us page for E-commerce website</title>
    <link rel="stylesheet" type="text/css" href="style2.css">
</head>

<body>
    <div class="contact-box">
        <form>
            <input type="text" class="input-field" placeholder="your name">
            <input type="text" class="input-field" placeholder="your email">
            <input type="text" class="input-field" placeholder="subject">
            <textarea type="text" class="input-field textarea-field" placeholder="your message">
                </textarea>
        </form>
        <button type="button" class="btn"></button>


    </div>
</body>

</html>
  
  # style of contact us page
  
  * {
    margin: 0;
    padding: 0;
}

.body {
    background-color: #efefef;
    font-family: sans-serif;
}

.contact-box {
    width: 500px;
    background-color: #efefef;
    box-shadow: 0 0 20px 0 #999;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    position: absolute;
    height: 300px;
}

.form {
    margin: 50px;
    height: 100px;
    margin-top: 20px;
    padding-left: 10px;
    border: 3px solid #777;
    outline: none;
}

.textarea-field {
    height: 50px;
    padding-top: 10px;
}

.btn {
    border-radius: 20px;
    color: #fff;
    margin-top: 18px;
    padding: 10px;
    background-color: #47c35a;
    font-size: 12px;
    border: none;
    cursor: pointer;
}
  
  
 #![Screenshot (2)](https://github.com/Kasanashivam07/E-Commerce-website/assets/120329017/20e7fe08-555c-46dd-adb7-c7dfb625ae70)
 connectivity of login page and contact us page using nodejs with mysql
  
  
  const mysql = require("mysql")
const express = require("express")
const app = express()
const connection = mysql.createConnection({
    host: "localhost",
    user: "root",
    password: "",
    database: "shivam"
})

// connection to database
connection.connect(function(error) {
    if (error) throw error
    else console.log("connected to the database successfully")
})

app.get("/", function(request, response) {
    res.sendFile(_dirname + "/index.html")
})
app.post("/", function(req, req) {
    connection.query("select * from loginuser where user_name=? and user_password=?", function(error, results, fields) {
        if (results.length > 0) {![Screenshot (2)](https://github.com/Kasanashivam07/E-Commerce-website/assets/120329017/47dbaab3-9e60-47ba-9faf-07e4381d01b4)
![Screenshot (6)](https://github.com/Kasanashivam07/E-Commerce-website/assets/120329017/85530d59-b675-4207-8f26-cc204b75a545)

            res.redirect("/welcome");
        } else {
            res.redirect("/");
        }
        res.end();

    })
})
  app.listen(4500)
  
  
  sql queries of mysql code
  
  
  ![image](https://github.com/Kasanashivam07/E-Commerce-website/assets/120329017/f30f709d-cd9c-418a-9b03-d8af344e4799)
![image](https://github.com/Kasanashivam07/E-Commerce-website/assets/120329017/428125f2-39cf-4abd-8203-981f421bc9c6)
![image](https://github.com/Kasanashivam07/E-Commerce-website/assets/120329017/69c5ef60-15bc-4732-8d5b-c3333396de8d)
![image](https://github.com/Kasanashivam07/E-Commerce-website/assets/120329017/a6d857d0-6ebc-404c-9f27-501f6d89cbe1)
![image](https://github.com/Kasanashivam07/E-Commerce-website/assets/120329017/640082f6-c539-49d8-b4ff-ebdd1925edcd)



