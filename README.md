<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>profile</title>
    <style>
        body{
        background:black;
        }
        h1{
            color:white;
            text-align:center;
        }
        p{
            color:yellow;
        }
        img{
            width: 200px;
            height: 400px;
        }
    </style>
</head>
<body>
    <h1>My Profile</h1>
    <p>
        <b>My name is moma, come from china. 19years old</b>
        </p></ br>
    <p>I passed my IELTS English test, then I came Irland to study my computer skill </p>
       </ br>
    <p>The weekend is my favourite rapper</p>
    </ br>
    <p>If you want to get my picture, please click the button below</p>
    </ br>
    <p>If you don't want to see me, you can turn off my picture.
    </p>
    </ br>
    <button onclick="document.getElementById('myImage').src=''">
        turn on
    </button>
    <img id="myImage" border="0" src="image.desktop/WechatIMG122.jpg" 
    style="text-align:center;">
    <button onclick="document.getElementById('myImage').src='/i/eg_bulboff.gif'">
        turn off
    </button>
    
</body>
</html>
