# Web-page-using-Html-and-CSS
You can get the code form here
<!---HTML CODE--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wel-Come To Nature View</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div class="main">
        <div class="navbar">
            
            <div class="icon">
                <img src="css/logo.png" alt="Loading">
                <h2 id="lg">Nature Love</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="#"></a>Home</li>
                    <li><a href="#"></a>About</li>
                    <li><a href="#"></a>Service</li>
                    <li><a href="#"></a>Design</li>
                    <li><a href="#"></a>Contact</li>
                </ul>
           `</div>

            <div class="search">
                <input type="search" name="" placeholder="Type to Search" id="src">
                <a href="#"><button class="btn">Search</button></a>
            </div>
        </div>
        
        <div class="content">
            <h1 class="">Nature is <br><span>source</span><br>of life</h1>
            <p class="para">
                Our planet is a sacred source of life; a living organism that is the common home for us and all the other living species. Economy is a subset of ecology.
                Nature, in the broadest sense, is the natural, physical, material world or universe. "Nature" can refer to the phenomena of the physical world, and also to life in general.
                To save natural resources join us.
            </p>
            <button class="cn"><a href="#">JOIN US</a></button>
           
            <div class="form">
                <h2>Login Here</h2>
                <input type="email" name="email" placeholder="Enter Email">
                <input type="password" name="password" placeholder="Enter password">
                <button class="btrn"><a href="#">Login</a></button>

                <p class="link">Don't have an account<br>
                <a href="#">Sign Up</a></p>
            </div>
        </div>
    </div>
</body>
</html>



<!---CSS Code--->

*{
    margin: 0;
    padding: 0; 
}
.main{
    background: linear-gradient(to top, rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%), url('front.jpg');
    background-position: center;
    background-size:cover;
    background-attachment:fixed;
    width:100%;
    height: 110vh;
}
.navbar{
    width: auto;
    height: 75px;
    margin-left: 30px;
}
.icon{
    width: 200px;
    float:left;
    height:70px;
}
img{
   width: 50px;
   height:50px;
   margin-top: 10px;
   float: left;
}
#lg{
    color:rgb(108, 253, 193);
    font-size: 24px;
    font-family:Arial;
    float: left;
    padding-top: 20px;
}

.menu{
    width:400px;
    float:left;
    height:70px;
}
ul{
    display:flex;
    align-self:center;
    float: left;
}
ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
    text-decoration: none;
    text-transform:uppercase;
    color:#fff;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    transition: 0.5s ease-in-out;
}

ul li:hover{
    color:aqua;
    transform:translateY(-5px);
    cursor:pointer;
}
.search{
    width:380px;
    float:left;
    margin-left: 270px;
}
#src{
    font-family: 'Times New Roman';
    width:200px;
    height: 40px;
    background: transparent;
    border:1px solid goldenrod;
    margin-top: 13px;
    color:#fff;
    border-right: none;
    font-size: 16px;
    text-align: center;
    float:left;
    padding:10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn{
    width: 100px;
    height: 40px;
    background: goldenrod;
    border:2px solid goldenrod;
    margin-top: 13px;
    color:#fff;
    font-size: 15px;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
    cursor: pointer;
}
.btn:focus{
    outline: none;
}
#src:focus{
    outline:none;
}
.content{
    width: auto;
    height: auto;
    margin: 30px;
    color:#fff;
    position: relative;
}
.content .para{
    width: 800px;
    height:auto;
    padding-left: 40px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
    text-align: justify;
}
.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 5%;
    letter-spacing: 2px;
}
.content .cn{
    width: 160px;
    height: 40px;
    background: #ff7200;
    border:none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 15px;
    cursor:pointer;
    transition: .4s ease;
}
.content .cn a{
    text-decoration: none;
    color:black;
    transition: .3s ease;
}
.cn:hover{
    background-color: #fff;
}
.content span{
    color:#42e63d;
    font-size: 65px;
}
.form{
    width: 250px;
    height: 300px;
    background: linear-gradient(to top,rgba(0,0,0,0.8)40%,rgba(0,0,0,0.8)40%);
    position: absolute;
    top:-20px;
    left: 870px;
    border-radius: 12px;
    padding: 25px;
}
.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: #fff;
    font-weight: bold;
    font-size: 22px;
    background-color: rgb(0, 253, 253);
    border-radius: 10px;
    margin: 3px;
    padding: 10px;
}

.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid #42e634;
    border-top: none;
    border-left: none;
    border-right: none;
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 24px;
    font-family: sans-serif;
}

.form input:focus{
    outline:none;
}

::placeholder{
    color:#fff;
    font-family: Arial;  
}

.btrn{
    width: 240px;
    height: 40px;
    background: #fff;
    border:none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 15px;
    cursor: pointer;
    transition: .5s ease;
}
.btrn a{
    color: black;
    text-decoration: none;
    font-weight: bold;
}
.btrn:hover{
    background: #ff7200;
    color: #fff;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align:center;
}
.form .link a{
    text-decoration: none;
    color: #ff7200;
}![front](https://user-images.githubusercontent.com/96160475/152549744-39177915-b061-42e4-9228-50e0dd4006ad.jpg)
!Also use any logo image or not for your Web page
