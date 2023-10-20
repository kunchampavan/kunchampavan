<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>navbar</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .navbar{
            display: flex;
            justify-content: space-between;
            margin-top: 10px;
            background-color: aqua;
        }
        .navbar ul li{
           margin-right: 30px;
           margin-left: 10px;
        }
        .navbar .links ul{
            display: flex;
            margin-top: 20px;
            margin-left: 25px;
        }
        .navbar .links ul li{
            list-style: none;
            margin-left: 20px;
        }
        .navbar .links ul li a{
            text-decoration: none;
            font-weight: bold;
        }
        .navbar .btns{
            margin-top: 20px;
            margin: 30px;
        }
        .navbar .btns button{
            padding: 5px;
            border-radius: 1px;
            color: rgb(204, 215, 224);
            background-color: rgb(29, 29, 182);
        }
        .navbar2{
            text-align: center;
            margin-top: 150px;
        }
        .navbar2 p{
            text-align: justify;
        }
        .navbar.logo img{
            position: absolute;
        
        }
    </style>
</head>
<body>
    <div class="navbar">
       <div class="logo">
         <img src="/4 to 5 pm/7evfgknj.png" alt="">
       </div>
       <div class="links">
          <ul>
            <li><a href="">home</a></li>
            <li><a href="">contact</a></li>
            <li><a href="">about</a></li>
            <li><a href="">map</a></li>
          </ul>
       </div>
       <div class="btns">
          <button>sing up</button>
          <button>sing in</button>
       </div>
    </div>
    <div class="navbar2">
        <img src="Home-Services-Blog-Inline-Promotion-BUY-02.png" alt="">
        <h1> 1.My Home Construction Private Limited</h1>
        <p>Known for its audacity to break away from the mould and knack for creative combinations, My Home Construction Private Limited has a three-decade-long history of excellence. Today, 21 illustrious addresses attest to the brand’s ability in constructing gated communities. 

            My Home Hub, 8th Floor, Block-3, Hitech City Road, Next to Cyber Towers, Madhapur, Telangana 500081
            
            Contacting: 040 6688 8888</p>
    </div>
</body>
</html>
