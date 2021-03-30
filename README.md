<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mark's Gym</title>
</head>
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@800&display=swap" rel="stylesheet">
<style>
    body{
        color: white;
        margin: 0px;
        padding: 0px;
        background: url('abs-1850926_1280.jpg');
        background-size: auto;
        font-family: 'Baloo Bhai 2', cursive;
        background: contain 200px 500px;
    }
    .left{
        /* border: 2px solid red; */
       display: inline-block ;
       position: absolute;
       left: 40px;
        top: 20px;
    }
    .mid{
        /* border: 2px solid red; */
        display: block ;
        width: 50%;
        margin: 20px auto;
    }
    .right{
        position: absolute;
        /* border: 2px solid red; */
        display: inline-block ;
        right: 34px;
        top: 33px;
    }
    .navbar{
        display: inline-block;
    }
    .navbar li{
        font-size: 20px;
        display: inline-block;
    }
    .navbar li a{
        color: white;
        text-decoration: none;
        padding: 34px 23px;
    }
    .navbar li a:hover{
        text-decoration: underline;
        color: rgb(194, 140, 25);
    }
    .left img{
        width: 136px;
         filter: invert(100%);
    } 
    .left div{
        line-height: 19px;
        font-size: 20px;
        text-align: center;
    }
    .btn{
        margin-bottom: 20px;
        font-family: 'Baloo Bhai 2', cursive;
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }
    .btn:hover{
        background-color: grey;
    }
    .container{
        /* border: 2px soid green; */
        border: 2px solid white;
        margin: 97px 734px;
        padding: 75px;
        width: 40%;
        border-radius: 28px;
    }
    .form-group input{
        font-family: 'Baloo Bhai 2',cursive;
        text-align: center;
        display: block;
        width: 508px;
        padding: 6px;
        border: 2px solid black;
        margin: 11px auto;
        font-size: 21px;
        border-radius: 8px;
    }
    .container h1{
        text-align: center;;
    }
    .container button{
        display: block;
        width: 71%;
        margin: 20px auto;

    }
   
</style>
<link rel="stylesheet" href="style.css">
<body>
    <header class="header">
        <div class="left">
            <img src="img/bg.jpg" alt="">
            <div>Mark's Gym</div>
        </div>
        <div class="mid">
            <ul class="navbar">
                <li> <a href="#" class="active">Home</a></li>
                <li> <a href="#">About Us</a></li>
                <li> <a href="#">Fitness Calculator</a></li>
                <li> <a href="#">Contact Us</a></li>
            </ul>
        </div>
        <div class="right">
            <button class="btn">Call us now</button><button class="btn">Email us</button>
        </div>
        
    </header>
    <div class="container">
        <h1>
            Join the best gym of Dehradun NOW
        </h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter Your Locality">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>

</body>
</html>
