# bharat-intern-task-2
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NETLIX CLONE</title>
    <style>
        body {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            margin: 0;
            padding: 0%;
            color: #000;
        }

        .img-logo {
            width: 12%;
        }

        .navbar {
            height: 10vh;
            background: color #000;
            justify-content: space-between;
            padding-left: 2wh;
            padding-right: 2wh;
        
            color: #fff;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .navbar image {
            height: 40px;
            margin-right: 10px;
            background-color: #0a0909;
        }

        .navbar ul {
            list-style: none;
            display: flex;
            align-items: center;
            margin: 0;
            padding: 0;
        }

        .navbar ul li {
            margin-left: 20px;
        }

        .navbar ul li:first-child {
            margin-left: 0%;

        }

        .navbar ul li a {
            color: #0a0909;
            text-decoration: none;
            margin-left: 20px;
        }

        .sign-in-box {
            background-color: #e50914;
            padding: 10px;
            margin-left: auto
        }

        .sign-in-box a {
            color: #fff;
            text-decoration: none
        }
        .main-container{
            width: 100%;
            height: 90vh;
        }
        .main-titles-container{
            color: #fff
        }



        .hero {
            
            background-position: ;
            background-image:radial-gradient(rgba(0,0,0,0.4),rgba(0,0,0,0.8)), url("netflixteaser.png");
            color: #fff;
            background-size cover;
            height: 600px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items centre padding: 40px;
            

        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-align: center;


        }
        .hero h2{
            text-align: center;
            font-size: 32px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 20px;
            text-align: center;
        }
        .hero a{
            text-align: center;
        }


        .cta-button {
            background-color: #e50914;
            color: #fff;
            font-size: 24px;
            padding: 10px 1px;
            border: none;
            border-radius: 2px;
            cursor: pointer;
            text-decoration: none;
        }

        .footer {
            background-color: #000;
            padding: 20px;
            color: #fff;
            text-align: center;
        }
    </style>
</head>

<body>

    <header class="navbar">
        <img class="img-logo" src="Netflix-Brand-Logo.png" ;alt="Netflix logo">
       
        <ul>

            <li><a href="#">HOME</a></li>
            <li><a href="#">TV SHOWS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">LATEST</a></li>
            <li><a href="#">MY LIST</a></li>
        </ul>
        <div class="sign-in-box">
            <a href="#">Sign-In</a>


        </div>
    </header>
    <section class="hero" >
        <div class="main container"></div>
    <div class="main-titles-container"></div>
       <h1  class="main title">Unlimited movies, TV shows and more</h1>
        <h2  class="main-subtitle">Watch anywhere. Cancel anytime..</h2>
        <p class="main-call-to-action">Ready to watch? Enter your email to create or restart your membership.</p>
        <a class="cta-button" href="#">start your free Trial</a>

    </section>;
    
    </section>
    <footer class="footer">
        <p>&copy;2023 Netflix clone.All rights reserved</p>
    </footer>

</body>

</html>
