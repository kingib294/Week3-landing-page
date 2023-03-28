# Week3-landing-page

<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> GRANDEUR </title>
        <style>
            header{
                background-color: black;
                border-style: double;
                border-bottom: 0px;
                border-color: brown;
                margin-top:0%;
                margin-bottom:0px;
                padding: 0%;
                justify-content: space-around;
            }
            .topnav{
                
                overflow: hidden;
                background-color:brown;
            }
            .topnav a{
                float: left;
                display: block;
                color: rgba(252, 252, 252, 0.87);
                text-align: center;
                padding: 14px;
                font-size: 17px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                font-weight: bolder;
            }
            .topnav a:not(:first-child){
                margin-left: 100px;
            }
            .topnav a:hover{
                background-color: rgb(9, 26, 26);
            }
            .topnav .icon{
                display: none;
            }
            body {
                background-color: black;
               
                color: antiquewhite;
            }
            #logo {
                padding: 0%;
                margin: o%
                display: flex;
                justify-content: space-around;
                 flex-wrap: wrap;;
            }
            .pic {
                width: 300px;
                border-style: groove;
                border-color: brown;
                border-radius: 30px;
            }
            .pic:hover {
                opacity: 0.5;
            }
            #about{
                border-style: ridge;
                background-color: black;
                border-top: 100%;
                border-color: brown;
                font-family: cursive;
                justify-content: space-around;
            }
            #buyNow{
                backdrop-filter: blur(16px) saturate(180%);
                -webkit-backdrop-filter: blur(16px) saturate(180%);
                background-color: rgba(160, 11, 11, 0.25);
                border-radius: 12px;
                border: 1px solid brown;  
                padding: 12px;  
                filter: drop-shadow(0 30px 10px rgba(184, 49, 49, 0.125));
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content:center;
                text-align: center;
            }
            #buyNow:hover{
                background-color: antiquewhite;
                color: black;
            }
            
            #set{   
                color: antiquewhite;
                background-color: black;
                background-size: auto;
                border-radius: 12px;
                border: 1px solid brown;  
                padding: 12px;  
                filter: drop-shadow(0 30px 10px rgba(184, 49, 49, 0.125));
                display: flex;
                flex-direction: column;
                align-items: left;
                justify-content:left;
                text-align: center;
                width: 200px;
            }
            
        </style>
    </head>
    <body>
        <header>
            <div class="topnav" id="myTopnav">
            
                <a href="#home" class="active">Home</a>
                
                <a href="#news">News</a>
                <a href="#hotDeals">Hot Deals</a>
                <a href="#contact">Contact</a>
                <a href="#about">About</a>
                
                <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                  <i class="fa fa-bars"></i>
                </a>
            </div>
    
            <div id="logo">
                <center>
                    <img src=".\Img\logo.png" alt="" style="width: 100px;">
                </center>
                
                <h1 style="font-family: fantasy; color: rgb(9, 45, 122); text-align: center; font-style: normal;"> GRAND TECH </h1>
                <p style="font-family: monospace; color: rgb(26, 38, 211); text-align: center; font-style: italic;">Luxury gadget shop</p>
            </div>
            
           </header>
           <main>
            <section>
                <div id="about">
                    <nav>
                 
                        <h3> Our Services</h3>
                        <ul>
                            <a href="#Sales"><li> Sales</li></a>
                            <a href="#maintenance"><li> maintenance</li></a>
                            <a href="#upgrade"> <li>upgrade</li></a>
                        </ul>
                        </nav>
                </div>
                <div>
                    <center>
                        <h1 style="color:red;">Iphone</h1>
                    <img src=".\Img\pic1.jpg" class="pic">
                    <center><button id="buyNow">Add to cart</button></center>
                        <br>
                    <img src=".\Img\pic2.jpg" class="pic">
                    <center><button id="buyNow"> Add to cart</button></center>
                       <br>
    
                    <img src=".\Img\pic3.jpg" class="pic">
                    <center><button id="buyNow">Add to cart</button></center>
                    </center>
                </div>
            </section>
            <section>
                    <P>Subscribe to our newsletter for more updates</p>
                    <form onsubmit="myFunction()">
                       
                            <div id="set">
                                <label for="Fullname" class="form">Fullname</label>
                                <br>
                                <input type="text" name="Fullname" id="Fullname">
                                <br>
                                <label for="Email" class="form">Email</label>
                                <br>
                                <input type="Email" name="Email" id="Email" required>
                                <br>
                                <label for="Phone number" class="form">Phone number</label>
                                <br>
                                <input type="Phone number" name="Phone number" id="Phone number">
                            <br>
                            <p>Gender</p>
                            <select id="Gender">
                                <option value="Male">Male</option>
                                <option value="Female">Female</option>
                            </select>   
                            <br>
                            <label for="Password">Password</label>   
                            <input type="text" name="Password" id="Password">
                            <button class="Submit" style="border-radius: 12px; border-color: brown; width: 100px;">Submit</button>
                        </div> 
                    </form>
                    <script>
                        function myFunction() {
                            alert ("Submitted")
                        }
                    </script>
            </section>
           </main>
           <footer style="color:whitesmoke; text-align: center;">cc: King IB</footer>
    </body>
