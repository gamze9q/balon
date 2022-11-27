<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="new.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class="hero">
        <div class="navbar">
            <img src="logo.png" class="logo">
            <button type="button">Sing Up</button>
        </div>
        <div class="content">
            <small>Welcome to our</small>
           <h1>World's<br>Creavite Studio</h1>
           <button type="button">Take a tour</button>
        </div>
        <div class="side-bar">
            <img src="menu.png" class="menu">

            <div class="social-links">
                <img src="fb.png">
                <img src="tw.png">
                <img src="fb.png">
            </div>

            <div class="useful-links">
                <img src="share.png">
                <img src="info.png">
            
            </div>
            
        </div>


        <div class="bubble">
            <img src="bubble.png">
            <img src="bubble.png">
            <img src="bubble.png">
            <img src="bubble.png">
            <img src="bubble.png">
            <img src="bubble.png">
            <img src="bubble.png">
        </div>



    </div>

</body>
</html>



*{
    margin: 0;
    padding: 0;
    font-family: seans-serif;
}
.hero{
    width: 100%;
    height: 100vh;
    background-image: url(x.png);
    background-size: cover;
    background-position: center;
    position: relative;
    overflow: hidden;
}
.logo{
    width: 100px;
    cursor: pointer;
}
.navbar{
    width: 85%;
    height: 15%;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
button{
    color: #fbfcfd;
    padding: 10px 25px;
    background: transparent;
    border: 1px solid #fff;
    border-radius: 20px;
    outline: none;
    cursor: pointer;
}
.content{
    color: #fbfcfd;
    position: absolute;
    top: 50%;
    left: 8%;
    transform: translateY(-50%);
    z-index: 2;
}
h1{
    font-size: 80px;
    margin: 10px 0 30px;
    line-height: 80px;
}
.side-bar{
    width: 50px;
    height: 100vh;
    background: linear-gradient(00545d, #000729);
    position: absolute;
    right: 0;
    top: 0;
}
.menu{
    display: block;
    width: 25px;
    margin: 40px auto 0;
    cursor: pointer;
}
.social-links img useful-links img{
    width: 25px;
    margin: 5px auto;
    cursor: pointer;
}
.social-links{
    width: 50px;
    text-align: center;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
}
.useful-links{
    width: 50px;
    text-align: center;
    position: absolute;
    bottom: 30px;
}
.bubbles img{
    width: 50px;
    animation: bubble 7s linear infinite;
}
.bubble{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-around;
    position: absolute;
    bottom: 0;
 }
 @keyframes bubble{
    0%{
        transform: translateY(0);
        opacity: 0;        
    }
    50%{
         opacity: 1;
    }
    70%{
         opacity: 1;
    }
    100%{
    transform: translateY(-80vh);
    opacity: 0;
 }


 }

.bubbles img:nth-child(1){
    animation-delay: 2s;
}
.bubbles img:nth-child(2){
    animation-delay: 1s;
}
.bubbles img:nth-child(3){
    animation-delay: 3s;
}
.bubbles img:nth-child(4){
    animation-delay: 4s;
}
.bubbles img:nth-child(5){
    animation-delay: 3s;
}
.bubbles img:nth-child(6){
    animation-delay: 6s;
}
.bubbles img:nth-child(7){
    animation-delay: 7s;
}



