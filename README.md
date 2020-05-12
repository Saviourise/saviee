<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
        <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
        <link href="https://fonts.googleapis.com/css?family=Oswald|Raleway&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel='stylesheet' href='https://use.fontawesome.com/releases/v5.5.0/css/all.css' integrity='sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU' crossorigin='anonymous'>
        
        <!-- CSS start -->
        
        <style>
            body {
    font-family:Raleway;
    background-image:url(https://scontent-los2-1.xx.fbcdn.net/v/t1.0-9/fr/cp0/e15/q65/96381524_1081575782215343_476000891724365824_n.jpg?_nc_cat=103&_nc_sid=110474&efg=eyJpIjoidCJ9&_nc_eui2=AeF4_LuxuAyQ_88B0E--Vpl3Jzxj2fKziksnPGPZ8rOKS5_vAyNx4yyKK7kVFzxTgGdDKl2IWnassqA955kRHJCb&_nc_oc=AQnO4J8nbIWuiAoWb5WtLcGANUrqHF2b_-hXJFDzQTy6ihBenhTBDnQpp7MXDMD8gpE&_nc_ht=scontent-los2-1.xx&_nc_tp=14&oh=8a74c2787ca3c6f4bfcb23b0e83d5c89&oe=5EDE96AA);
    background-size:cover;
    background-repeat:no-repeat;
    filter: blur(19px);
    -webkit-filter: blur(19px);
}
h1 {
    text-align:center;
    font-weight:bolder;
}
form {
    text-align:center;
    border:none;
}
input {
    width:290px;
    outline:none;
    font-size:18px;
    border:none;
}
p {
    text-align:center;
    padding:10px;
    font-size:17px;
    font-weight:bolder;
}
#searchbtn {
    width:70px;
    background-color:green;
    color:white;
    font-weight:bolder;
    font-size:15px;
    height:28px;
}
div {
    font-weight:bolder;
    font-size:18px;
}
#close {
    color:white;
    font-size:17px;
    margin-left:-5px;
    background-color:red;
    font-weight:bolder;
    border:none;
    outline:none;
}
#oc {
    text-align:center;
    background-color:cyan;
    color:black;
    font-weight:bolder;
    float:center;
    font-size:17px;
    margin-bottom:10px;
    border:none;
    outline:none;
}
li {
    width:150px;
    margin-left:-px;
    margin-top:-10px;
    padding-bottom:10px;
    padding-top:10px;
    font-size:17px;
    font-weight:bolder;
}
span {
    padding:10px;
    font-size:20px;
    font-weight:bolder;
}
p#a {
    padding:20px;
    font-size:20px;
}
td {
    height:27px;
}
#homebtn {
    background-color:red;
    color:white;
    font-weight:bolder;
    margin:10px;
    border:none;
    outline:none;
}
        </style>
        
        <!-- CSS end --
        
        
        <!-- JavaScript start -->
        
        <script>
            $(function() {
    $("#close").hide();
    $("ul").hide();
    $(".ot").hide();
    $("#closeot").hide();
    $("#Africa").hide();
    $("#Asia").hide();
    $("#Europe").hide();
    $("#NorthAmerica").hide();
});
function oc() {
    $("#close").show(600);
    $("ul").show(600);
    //$("form").marginTop(150px);
}
function clos() {
    $("ul").hide(600);
    $("#close").hide(600);
}
function africa() {
    $("#Africa").show();
    $("#home").hide();
    $("#Asia").hide();
    $("#Europe").hide();
    $("#NorthAmerica").hide();
    $("ul").hide(600);
    $("#close").hide(600);
}
function asia() {
    $("#Africa").show();
    $("#home").hide();
    $("#Asia").hide();
    $("#Europe").hide();
    $("#NorthAmerica").hide();
    $("ul").hide(600);
    $("#close").hide(600);
}
function europe() {
    $("#Africa").show();
    $("#home").hide();
    $("#Asia").hide();
    $("#Europe").hide();
    $("#NorthAmerica").hide();
    $("ul").hide(600);
    $("#close").hide(600);
}
function northamerica() {
    $("#Africa").show();
    $("#home").hide();
    $("#Asia").hide();
    $("#Europe").hide();
    $("#NorthAmerica").hide();
    $("ul").hide(600);
    $("#close").hide(600);
}
function gohome() {
    $("#home").show(600);
    $("#Africa").hide();
    $("#Asia").hide();
    $("#Europe").hide();
    $("#NorthAmerica").hide();
    $("ul").hide(600);
    $("#close").hide(600);
}
        </script>
        
        <!-- JavaScript end -->
        
    </head>
    <body>
    
    
    
    <!-- Home page -->
    
    
    
    <div id="home">
        <h1>Welcome to Weather Today</h1>
        </br>
        
        <!-- Search area in home page -->
        
        <form style="margin-top:px;" onsubmit="submitsearch()">
        <input id="input" type="Search" placeholder="Search City" required>
        <input id="searchbtn" type="submit" value="search">
        </form>
        </br>
        
        <!-- Other Cities in home page-->
        
        <div class="container">
            <div class="row">
                <div class="col-sm-4">
                    <button onclick="oc()" id="oc">Other Cities </button>
            
                    <button onclick="clos()" id="close">&times</button>
                    <ul>
                        <li onclick="africa()">Africa</li>
                        <li onclick="asia()">Asia</li>
                        <li onclick="northamerica()">North America</li>
                        <li onclick="europe()">Europe</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <!-- home page table -->
        
        <div class="container table-responsive">
      <table class="table table-striped">
        <thead>
          <tr>
            <th>City</th>
            <th>Weather Type</th>
            <th>Temp(°c) </th>
                       
          </tr>
        </thead>
        <tbody>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          </tbody>
        </table>
    </div>
        
    </div>
    
    <!-- End of Home page -->
    
    
    
    
    
    
    <!-- City searched for -->
    
    
    
    
    
    
    <div id="Africa">
    
    <!-- home button -->
    
    <button id="homebtn" onclick="gohome()">Go back home</button>
    
        <!-- Head -->
        
        <h1>Welcome to Weather Today</h1>
        </br>
        
        <!-- Search area -->
        
        <form onsubmit="submitsearch()">
        <input id="input" type="Search" placeholder="Search City" required>
        <input id="searchbtn" type="submit" value="search">
        </form>
        </br>
       
        <!-- Other Cities -->
        
        <div class="container">
            <div class="row">
                <div class="col-sm-4">
                    <button onclick="oc()" id="oc">Other Cities </button>
            
                    <button onclick="clos()" id="close">&times</button>
                    <ul>
                        <li onclick="africa()">Africa</li>
                        <li onclick="asia()">Asia</li>
                        <li onclick="northamerica()">North America</li>
                        <li onclick="europe()">Europe</li>
                    </ul>
                </div>
            </div>
        </div>
        </br>
        
         <!-- Search result -->
         
                    <p id="sr">Search result for </p>
    <div class="container table-responsive">
      <table class="table table-striped">
        <thead>
          <tr>
            <th>City</th>
            <th>Weather Type</th>
            <th>Temp(°c) </th>
                       
          </tr>
        </thead>
        <tbody>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
           <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
          <tr>
              <td></td>
              <td></td>
              <td></td>
          </tr>
        </tbody>
        </table>
    </div>
    </br>
    
        <!-- Footer -->
        
        <span id="b">About Blog </span>
        <span id="c">Contact Us</span>
        <span id="d">Leave a comment</span>
        </br>
        <p id="a">Visit  <a href="https://www.weather-today.com"  target="blank">www.weather-today.com</a> for more info</p>
    </div>
    
    <!-- End of Search result-->
