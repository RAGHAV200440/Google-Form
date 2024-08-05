# Google-Form
code for google for html and css
DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet"href="google sheet.css">
</head>
<body>
    <div class="container">
        <form method="post" action="https://script.google.com/macros/s/AKfycbzeyHho_VWVtLhJnHwB5-B3l5E1vldHeA3pd0I6QuPfybuJ7aIMQ5IMKCtrr3s2yrcq/exec" name="contact-form">
           <p<h5>contact Us</h5></p>
            <input type="test" name="your-name" placeholder="Name">
            <input type="test" name="your-number" placeholder="Number">
            <input type="test" name="your-Email" placeholder="Email">
            <textarea name="message" rows="7" placeholder="Your Messge"></textarea>
            <input type="submit" value="submit" id="submit">
        </form>
      </div>
      

    <script src="Google sheet.js"></script>
</body>
</html>
CODE FOR CSS
*{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
    font-family:'poppins', sans-serif;
    font-size: 18px;
}
body{
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
.container{
    width: 500px;
    padding: 30px;
    border: 1px solid #eeeeee;
    border-radius: 10px;
    background-color: #5a005b;
}
h4{
    margin-bottom: 10px;
    font-size: 24px;
    color: rgba(255, 255, 255, 0.023);
}
input{
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
}
textarea{
    width: 100%;
    padding: 10px;
}
#submit{
    border: none;
    background-color: orangered;
    color: white;
    width: 200px;
    margin-top: 10px;
    border-radius: 5px;
}
#submit:hover{
    background-color: #333333;
}
