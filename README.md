<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
        Wells Fargo
    </title>
    <link rel="stylesheet" href="wells.css">
    <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.1/css/fontawesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

    <link rel="shortcut icon" href="img 4.jpg" type="image/x-icon">
    <style>
      body{
    padding: 0%;
    box-sizing: border-box;
}
.head{
    background-color: rgb(212, 58, 58);
    height: 70px;
}
.fargo{
    color: white;
    font-weight: bold;
    padding: 18px;
    font-size: 25px;
    font-family: 'Times New Roman', Times, serif;
    margin-right: 800px;
    text-align: center;
}
.list{
    display: inline-block;
    padding: 20px;
}
.list li{
    display: inline;
    color: white;
    margin: 20px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.list li a{
    padding: 10px;
    text-decoration: none;
    color: white;
}
.list li a:hover{
    text-decoration: underline;
    
}
.search{
    height: 30px;
    width: 100px;
    border: none;
    border-bottom: 1px solid black;
    border-right: 1px solid black;
    border-radius: 10px;
    background-color: rgb(212, 58, 58);
    color: white;
    margin-right: 50px;
}
.signon{
    width: 100px;
    height: 30px;
    border-radius: 12px;
    border: none;
    background-color: white;
    font-weight: bold;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    margin-left: 700px;
}
.signon:hover{
    text-decoration: underline;
}
.personal{
    margin: 20px;
    margin-left: 60px;
}
.personal li{
    display: inline;
    padding: 25px;
}
.personal li:first-child{
    padding: 0px;
}
.personal li a{
    text-decoration: none;
    color: rgb(59, 55, 55);
    opacity: 0.2px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.personal li a:hover{
text-decoration: underline;
}
.check li{
    display: inline;
    padding: 20px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    margin-top: 30px;
}
.check li:hover{
text-decoration: underline;
}
.simplify{
    background-image: url(bg\ image.jpg);
    height: 600px;
    background-repeat:no-repeat ;
    background-position: center;
    background-size: cover;
}
.good{
    background-color: white;
    margin-top: 40px;
    float: left;
    height: 450px;
    width: 300px;
    margin-left: 10px;
    border-radius: 10px;
    letter-spacing: 0.12px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    padding-left: 17px;
    padding-top: 20px;
}
.afternoon{
    font-size: 25px;
    color: black;
    padding-top: 30px;
}
.username{
    margin-top: 27px;
    /* The next two lines have been added to ensure that when keying in your name a border does not appear all round the text but only on the bottom part*/
    border: none;
    border-bottom: 1px solid black;
    width: 250px;
    height: 20px;
    font-size: 20px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

}
.username:focus{
    outline: none;
    /* the outline none has been used here to avoid the border that appears when typing inside the input which is usernamer in this case. Also, focus has been used here which has the same function as active in buttons*/

}
.password{
    margin-top: 27px;
    border: none;
    border-bottom: 1px solid black;
    width: 250px;
    height: 20px;
    font-size: 20px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.password:focus{
    outline: none;
}
.life{
   padding: 40px;
   text-align: center;
}
.your{
    font-size: 50px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    padding-bottom: 30px;
}
.money{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.checkbox{
    margin-top: 20px;
    width: 20px;
    height: 20px;
}
.button{
    margin-top: 20px;
    margin-left: 10px;
    height: 34px;
    width: 97px;
    border: none;
    border-radius: 10px;
    background-color: rgb(236, 12, 12);
}
.button:hover{
    text-decoration: underline;
    background-color:  rgb(214, 47, 47);
   
}
.enroll{
    display: inline;
}
.signin{
    margin-top: 20px;
    margin-left: 70px;
    height: 34px;
    width: 97px;
    border: none;
    border-radius: 10px;
}
.signin a{
    text-decoration: none;
    color: black;
}
.signin a:hover{
    text-decoration: underline;
}
.forgot{
    margin-top: 30px;
    background-color: rgb(248, 246, 243);
    padding: 5px;
}
.forgot a{
    text-decoration: none;
    color: black;
}
.forgot a:hover{
    text-decoration: underline;
}
.now {
    text-align: center;
    margin-left: 690px;
    margin-top: 200px;
    height: 55px;
    width: 200px;
    background-color: white;
    border-radius: 20px;
    border: 1px solid black;
}
.now a{
    font-size: 20px;
    text-decoration: none;
    color: black;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.now a:hover{
    color: white;
}
.now:hover{
    background-color: black;
    color: rgb(238, 232, 232);
}
.mortgage{
    display: inline;
    height: 300px;
    width: 500px;
    background-color: rgb(41, 223, 102);
    margin: 20px;
    border: 1px solid black;
}
.find{
    height: 250px;
    width: 250px;
    background-color: rgb(235, 230, 225);
    margin: 30px;
    border-radius: 10px;
    padding: 20px;
    text-align: center;
    font-size: 20px;
    display: inline-block;
    position: relative;
    margin-top: 50px;
}
.more{
    text-decoration: none;
    color: black;
}
.more:hover{
    text-decoration: underline;
}
.right{
    height: 250px;
    width: 250px;
    background-color:  rgb(235, 230, 225);
    display: inline-block;
    margin: 30px;
}
.allimg{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
.assets{
    width: 300px;
    height: 350px;
    background-color: rgb(243, 240, 237);
    margin: 30px;
    padding: 20px;
    border-radius: 10px;
    display: inline-block;
}
.assetsimg{
    justify-content: space-evenly;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
.loans{
    display: inline-block;
    width: 300px;
    height: 350px;
    background-color: rgb(243, 240, 237);
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
}
.loanimg{
    justify-content: space-around;
}
.education{
    display: inline-block;
    width: 300px;
    height: 350px;
    background-color: rgb(243, 240, 237);
    margin: 30px;
    padding: 20px;
    border-radius: 10px;
}
.bodyheader{
    text-align: center;
    font-weight: lighter;
    font-size: 45px;
}
#support{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
.image3{
    border-radius: 10px;
    margin: 30px;
    border: 1px solid black;
    width: 400px;
}
.girl{
    border-radius: 10px;
    width: 400px;
}
.spend{
    font-weight: bold;
    font-size: 22px;
    padding: 10px;
    text-align: center;
}
.four{
    padding: 20px;
    text-align: center;
    margin-bottom: 10px;
}
.manage{
    margin: 20px;
    width: 320px; 
    height: 40px;
    align-items: center;
    margin-left: 42px;
    border-radius: 20px;
    background-color: white;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 15px;
    font-weight: bold;
}
.saving{
    color: black;
    text-decoration: none;
    flex: 1;
    justify-content: space-evenly;
}
.saving:hover{
    text-decoration: underline;
    color: white;
}
.manage:hover{
    background-color: black;
    color: white;
    transition-duration: 2s;
}
.manage:active{
    background-color: aquamarine;
}
 .reduce{
    border-radius: 10px;
    margin: 30px;
    border: 1px solid black;
    width: 400px;
    display: inline-block;
 }
.image6{
    border-radius: 10px;
    width: 400px;
}
.debt{
    margin: 20px;
    text-align: center;
    font-size: 22px;
    font-weight: bold;
}
.discover{
    margin-left: 10px;
    font-size: 20px;
}
.build{
    margin: 20px;
    width: 320px; 
    height: 40px;
    align-items: center;
    margin-left: 42px;
    border-radius: 20px;
    background-color: white;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 14px;
    font-weight: bold;
}
.live{
color: black;
text-decoration: none;
}
.live:hover{
    text-decoration: underline;
    color: white;
}
.build:hover{
    background-color: black;
    transition-duration: 2s;
    color: white;
}
.tools{
    border-radius: 10px;
    margin: 30px;
    border: 1px solid black;
    width: 400px;
    display: inline-block;
}
.img5{
    border-radius: 10px;
    width: 400px;  
}
.get{
    margin: 20px;
    width: 320px; 
    height: 40px;
    border-radius: 20px;
    background-color: white;
    font-size: 20px;
    font-weight: bold;
}
.digital{
    margin-left: 10px;
    font-size: 20px;
}
.toolkit{
    margin: 20px;
    width: 320px; 
    height: 40px;
    align-items: center;
    margin-left: 42px;
    border-radius: 20px;
    background-color: white;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 14px;
    font-weight: bold;
}
.litoolkit{
    color: black;
    text-decoration: none;
    
}
.toolkit:hover{
    background-color: black;
    text-decoration: underline;
    color: white;
    transition-duration: 2s;
}
.litoolkit:hover{
    color: white    ;
}
.palm{
width: 1000px;
height: 700px;
background-color: rgb(130, 79, 177);
margin-left: 400px;
border-radius: 10px;
margin-bottom: 200px;
}
.hand{
    text-align: center;
    font-size: 40px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    padding: 20px;
    font-weight: bold;
    color: white;
}
.mobile{
    padding-left: 60px;
    margin: 20px;
    color: white;
    font-weight: bold;
    font-size: 20px;
}
.download{
    padding-left: 60px;
    margin: 20px;
    color: white;
    font-weight: bold;
    font-size: 30px;
}
.lastpart{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
}
.redmen{
    width: 616px;
    height: 580px;
    border: 1px solid black;
    border-radius: 15px;
}
.lastpart{
    border-radius: 15px;
}
.flowergirls{
    width: 616px;
    height: 580px;
    border: 1px solid black;
    border-radius: 15px;
}
.lastimg{
    border-radius: 15px;
}
.lasthead{
    margin: 20px;
    font-size: 20px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.whoweare{
    margin-top: 20px;
    margin-left: 13px;
    width: 200px;
    height: 40px;
    border-radius: 10px;
    background-color: white;
}
.aboutwellsfargo{
    text-decoration: none;
    color: black;
    font-size: 17px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.whoweare:hover{
    background-color: black;
    color: white;
    transition-duration: 1s;
}
.aboutwellsfargo:hover{
    color: white;
}
.verylast{
    margin: 20px;
    font-size: 20px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.wellsfargostories{
    margin-top: 20px;
    margin-left: 13px;
    width: 200px;
    height: 40px;
    border-radius: 10px;
    background-color: white;
}
.lastlink{
    text-decoration: none;
    color: black;
    font-size: 17px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.wellsfargostories:hover{
    background-color: black;
    color: white;
    transition-duration: 1s;
}
.lastlink:hover{
    color: white;
}
    </style>
</head>

<body>
    <div class="head">
        <span class="fargo">WELLS FARGO</span>
        <ul class="list">
            <li><a href="#">ATMs/Location</a></li>
            <li><a href="#">Help</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Espanol</a></li>
        </ul>
        <input type="search" class="search">
        <i class="fas fa-search"></i> <br>
    </div>
    <hr class="horizontal">
    </div>
    <div class="personal">
        <ul>
            <li><a href="#">Personal</a></li>
            <li><a href="#">Investing and Wealth Management</a></li>
            <li><a href="#">Small Business</a></li>
            <li><a href="#">Commercial Banking</a></li>
            <li><a href="#">Corporate & Investment Banking</a></li>
        </ul>
    </div>
    <div class="check">
        <ul>
            <li>Checking</li>
            <li>Savings & CDS</li>
            <li> Credit Cards</li>
            <li>Home Loans</li>
            <li>Personal Loans</li>
            <li>Auto Loans</li>
            <li>Premier</li>
            <li>Educational & Tools</li>
        </ul>
    </div>
    <div class="simplify">
        <form class="good" action="sign in">
            <span class="afternoon">
                Good afternoon <br>
            </span>
            Sign in to manage your accounts <br>
            <input class="username" type="text" placeholder="Username">
            <input class="password" type="password" placeholder="Password"> <br>
            <span class="save">
                <input class="checkbox" type="checkbox"> Save username <br>
            </span>
            <div class="enroll">
                <button class="button">
                    Sign in
                </button>
                <button class="signin">
                    <a href="#">Enroll</a>
                </button>
            </div>
            <div class="forgot">
                <a href="#">Forgot username or password? <br></a>
                <a href="#">Security Center <br></a>
                <a href="#">Privacy, Cookies and Legal</a>
            </div>
        </form>
        <p class="life">
            <span class="your">Simplify your life</span> <br>
            <span class="money">Your money's at hand with Everyday Checking</span>
        </p>
        <p1>
            <button class="now">
                <a href="#"> <b>Start now</b></a>
            </button>
        </p1>
    </div>
    <div class="links">
        <h6 class="bodyheader">
            Financial guidance and support
        </h6>
        <div id="support">
            <div class="image3">
                <img class="girl" src="img3.jpg" alt="an image is supposed to be here">
                <p class="spend">
                    Spend less. Save more. Relax more.
                </p>
                <p2 class="four">
                    These four steps could help you make it happen
                </p2>
                <button class="manage">
                    <a class="saving" href="#">
                        Manage spending and saving
                    </a>
                </button>
            </div>
            <div class="reduce">
                <img class="image6" src="img 6.jpg" alt="a father and a child image">
                <p class="debt">
                    Reduce debt. Build credit. Enjoy life.
                </p>
                <p class="discover">
                    Discover four steps that may help you reduce debt and strengthen credit
                </p>
                <button class="build">
                    <a class="live" href="#">
                        Build credit and reduce debt
                    </a>
                </button>
            </div>
            <div class="tools">
                <img class="img5" src="img 5.jpg" alt="a girl taking coffee while working on her laptop">
                <p class="get">
                    Get tools. Get tips. Get peace of mind.
                </p>
                <p class="digital">
                    Discover digital tools to help you budget, save, manage credit, and more
                </p>
                <button class="toolkit">
                    <a href="#" class="litoolkit">
                        Access the toolkit
                    </a>
                </button>
            </div>
        </div>
    </div>
    <div class="palm">
        <p class="hand">
            Banking in the palm of your hand
        </p>
        <p class="mobile">
            Our Wells Fargo Mobile® app gives you fast and secure access to your finances
            <br>
            <br>
            Check your account balance
            <br>
            <br>
            View your latest FICO® Score1
            <br>
            <br>
            Send and receive money with Zelle®2
            <br>
            <br>
        </p>
        <p class="download">
            Download our app
        </p>
    </div>
    <div class="lastpart">
        <div class="redmen">
            <img class="lastpart" src="last part.avif" alt="people carrying fargo image is supposed to be here.">
            <p class="lasthead">
                <b>Who we are </b> <br><br>
                Wells Fargo helps strengthen communities through diversity, equity, and inclusion, economic empowerment,
                and
                sustainability.
            </p>
            <button class="whoweare">
                <a class="aboutwellsfargo" href="#">About Wells Fargo</a>
            </button>
        </div>
        <div class="flowergirls">
            <img class="lastimg" src="last part 2.avif"
                alt="girls walking in a flower plantation image should be shown here">
            <p class="verylast">
                <b>Why we are committed to communities</b> <br> <br>
                We don't just serve our communities—we are our communities. We're committed to helping customers and
                neighborhoods
                across the country thrive.
            </p>
            <button class="wellsfargostories">
                <a class="lastlink" href="#">Wells Frago Stories</a>
            </button>
        </div>
    </div>
</body>

</html>
