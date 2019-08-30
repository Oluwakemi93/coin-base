<template>
<nav class="navigation">
  <h1>coinbase</h1>
  <div class="dropdown">
    <button class="dropbtn">Products &nbsp;<i class="fa fa-angle-down"></i></button>
    <div class="dropdown-content">
    <div class="left-side">
      <p id="every">FOR EVERYONE</p>
      <div id="a">
        <img src="../assets/coinbase-icon.png">
        <h4>Coinbase</h4>
        <p>Buy, sell, and use cryptocurrency</p>
      </div>
      <div id="b">
        <img src="../assets/wallet.png">
        <h4>Wallet</h4>
        <p>Store your own cryptocurrency</p>
      </div>
      <div id="c">
        <img src="../assets/usdcoin.png">
        <h4>USD Coin</h4>
        <p>Cryptocurrency with a stable price</p>
      </div>
      <div id="d">
        <img src="../assets/earn.png">
        <h4>Earn</h4>
        <p>Make money learning about crypto</p>
      </div>
    </div>
    <div class="right-side">
      <p id="advance">FOR ADVANCED TRADERS</p>
      <div id="e">
        <img src="../assets/pro.png">
        <h4 id="i">Pro</h4>
        <p id="j">Advanced cryptocurrency trading</p>
      </div>
      <p id="business">FOR BUSINESSES</p>
      <div id="f">
        <img src="../assets/commerce.png">
        <h4 id="i">Commerce</h4>
        <p id="j">Accept cryptocurrency payment</p>
      </div>
      <div id="g">
        <img src="../assets/custody.png">
        <h4 id="i">Custody</h4>
        <p id="j">Cryptocurrency custody for institutions</p>
      </div>
      <div id="h">
        <img src="../assets/ventures.png">
        <h4 id="i">Ventures</h4>
        <p id="j">Raise money for your crypto startup</p>
      </div>
    </div>
  
  </div>
</div>

<button id="price">Prices</button>

<div class="dropdown1">
<button class="dropbtn1">Company &nbsp;<i class="fa fa-angle-down"></i></button>
<div class="dropdown-content1">
<router-link class="link" to="/about">About us</router-link><hr>

<router-link class="link" to="/blog">Blog</router-link><hr>

<router-link class="link" to="/support">Support</router-link><hr>

<router-link class="link" to="/career">Careers</router-link>
</div>
</div>

<span class="link__wrapper2">
<router-link class="link" to="/signin">Sign in</router-link>
</span>

<span class="link__wrapper3">
<router-link class="link" to="/signup"><button>Get Started</button></router-link>
</span>
</nav>
</template>

<script>
export default {
name: 'Navbar',
methods: {
scroll() {
$(window).on("scroll", function() {
if($(window).scrollTop() > 20) {
$("header").addClass("active");
}
})
}
}
} 
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navigation {
  font-family: 'DM Sans', sans-serif;
  position: fixed;
  width:98.1vw;
  height:94px;
  left: 8px;
  top: 1%;
  background:rgb(6, 103, 208);
  margin:-8px 0px 0px -8px;
  justify-content: space-between;
}
.dropbtn {
background-color: rgb(6, 103, 208);
color: white;
padding: 16px;
font-size: 14px;
border: none;
}

.dropdown {
margin: 25px 0px 0px 290px;
position: absolute;
display: inline-block;
}

.dropdown-content {
display: none;
position: absolute;
background-color: #ffffff;
min-width: 799px;
height: 460px;
right: -355%;
color:black;
border-radius: 5px;
box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
z-index: 1;
}
.dropdown-content a {
color: black;
padding: 12px 16px;
text-decoration: none;
display: block;
}

.dropdown-content a:hover {background-color: #fff;
}

.dropdown:hover .dropdown-content {display: block;
}

.dropdown:hover .dropbtn {background-color: rgb(6, 103, 208);
}

.dropbtn1 {
background-color: rgb(6, 103, 208);
color: white;
padding: 16px;
font-size: 14px;
border: none;

}

.dropdown1 {
margin: 25px 0px 0px -20px;
display: inline-block;
font-family: Darker Grotesque;
}

.dropdown-content1 {
  display: none;
  position: fixed;
  background-color: #f1f1f1;
  min-width: 126px;
 box-shadow: 0px 4px 8px 0px rgb(236, 239, 241);
  z-index: 1;
}

.dropdown-content1 .link {
  display: block;
  color: rgb(5, 15, 25);
  font-size: 14px;
  font-weight: 400;
  padding: 6px 16px;
  text-decoration: none;
  border: none;
}

.dropdown-content1 a:hover {background-color: #fff;
}

.dropdown1:hover .dropdown-content1 {display: block;
}

.dropdown1:hover .dropbtn1 {background-color:rgb(6, 103, 208);
}
#price{
background-color: rgb(6, 103, 208);
color: white;
padding: 16px;
font-size: 14px;
border: none;
margin: 25px 0px 0px 380px;
}
.menu{
display: flex;
align-content: center;
justify-content: center;
flex: 1;
position: absolute;
left: 39.3%;
font-size:17px;
margin:20px 6px 0px 0px;

}
.active {
background: white;
-webkit-box-shadow: 0 1px 5px rgba(0, 0, 0, 0.25);
}
.link {
color: #fff;
padding: 0.5 3em;
text-decoration: none;
}
img {
padding: 0.5em 1em;
color: #fff;
float:left;
margin:24px 0px 0px 90px;
}
h1 {
padding: 0.5em 1em;
color: #fff;
float:left;
margin:24px 0px 0px 90px;
}
.menu #one{
background: rgb(6, 103, 208);
border: none;
color: #fff;
}
.menu #two{
background: rgb(6, 103, 208);
border: none;
color: #fff;
}
.link__wrapper2 {
padding: 0.5em 1em;
color: #fff;
float:right;
font-size:14px;
margin:30px 223px 0px 0px;
}
.link__wrapper3 {
padding: 0.5em 1em;
color: #fff;
float:right;
margin:18px -221px 0px 0px;
}
.link__wrapper3 button:hover {background-color: #fff;
}
.link__wrapper3 button:hover {color: #000;
}
button {
background: transparent;
padding: 0.65em 1em;
border-radius: 6px;
border: 1px solid white;
color: #ffffff;
height:42px;
width:110px;
}
#every{
margin: 15px 0px 0px 15px;
color: black;
}
p{
margin: 5px 0px 0px 0px;
color: #2d5986;
font-size: 16px;
width: 330px;

}
h4{
margin:5px 0px 0px 50px;
font-size: 16px;

}
#a{
margin: 25px 0px 0px 0px;
}
#b{
margin: 30px 0px 0px 0px;
}
#c{
margin: 30px 0px 0px 0px;
}#d{
margin: 30px 0px 0px 0px;
}
#e{
margin: -5px 0px 0px 0px;
}
#f{
margin: -10px 0px 0px 0px;
}
#g{
margin: 0px 0px 0px 0px;
}
.left-side{
float: left;
margin: 0px -10px 0px 17px;
}
.right-side{
float: right;
margin: 20px 10px 0px 0px;
}
.right-side img{
border-radius: 50%;
width: 50px;
margin: -5px 0px 0px 10px;

}
.left-side img{
border-radius: 50%;
width: 40px;
margin: -5px 0px 0px 0px;

}
#advance{
margin: -5px 0px 0px 15px;
color: black;
}
#j{
margin: 5px 0px 0px 0px;
color: #2d5986;
font-size: 16px;
width: 400px;

}
#i{
margin:25px 0px 0px 0px;
font-size: 16px;

}
#business{
margin: 18px 0px 0px 15px;
color: black;
}
.prod {
  position: relative;
  text-align: center;
  border: 1px solid white;
}
</style>