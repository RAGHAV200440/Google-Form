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


YOUTUBE THUMBNAIL CODE HTML VS CSS
       COMBINE   +    CODE 
BACKGROUND IMAGE LINK HTML VS CSS

<!DOCTYPE html>
<html>
<head>
	<title>Adding a Video</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<h1 id="title">Adding a Video</h1>
	<div id="background">
		<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSQp3gZJrupcx2bhZcxPIypylq8199ZcOp_qg&s" alt="Background Image">
	</div>
	<div id="video-container">
		<iframe src="https://www.youtube.com/embed/ly36kn0ug4k?si=CqN3ThsZKFdc0G4X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
	</div>
</body>
</html>

THUMBNAIL CODE CSS
     +
BACKGROUND CODE CSS

body {
	background-color: #f0f0f0; /* fallback background color */
	background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSQp3gZJrupcx2bhZcxPIypylq8199ZcOp_qg&s');
	background-size: cover;
	background-position: center;
	height: 100vh;
	margin: 0;
}

#title {
	color: #fff;
	font-size: 36px;
	text-align: center;
	margin-bottom: 20px;
}

#background {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100vh;
	z-index: -1;
}

#video-container {
	width: 50%;
	margin: 40px auto;
}

iframe {
	width: 100%;
	height: 300px;
	border: none;
}
