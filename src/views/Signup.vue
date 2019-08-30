<template>
  <div class="main-wrap">
    <nav id="navbar">
      <ul>
        <li class="coinbase"><h6>Coinbase</h6></li>
        <li><div class="dropdown"><p class="dropbtn">Products </p>
          <div class="dropdown-content">
                	<span class="left">
		<table>
			<tr>
        <p class="p3">for everyone</p>
				<td><img src="../assets/usdcoin.png" width="45" height="45"></td>
				<td>
					<dl>
						<dt>Coinbase</dt>
						<dd>Buy, sell, and use cryptocurrency</dd>
					</dl>
				</td>
			</tr>
		</table>
	</span>
	<span class="right">
		<table>
			<tr>
         <p class="p3">for advance traders</p>
				<td><img src="../assets/usdcoin.png" width="45" height="45"></td>
				<td>
					<dl>
						<dt>Pro</dt>
						<dd>Advanced cryptocurrency trading</dd>
					</dl>
				</td>
			</tr>
		</table>
	</span>
          </div>
        </div>
        </li>
        <li class="products"><p class="dropbtn">Prices</p></li>
        <li><div class="dropdown2"><p class="dropbtn2">Company</p>
          <div class="dropdown2-content">
            <router-link class="link" to="/about">About Us</router-link>
            <router-link class="link" to="/blog">Blog</router-link>
            <router-link class="link" to="/support">Support</router-link>
            <router-link class="link" to="/careers">Careers</router-link>
          </div></div>
        </li>
        <li class="sign-in"><router-link class="link" to="/signin">Sign In</router-link></li>
          <li class="signup"><router-link class="link" to="/signup">Get Started</router-link></li>
      </ul>
	</nav>
  <h2 class="createtxt">Create your account</h2>
  <div class="createbox">
    
      <div>
        <span class="left1">
          <label>First name</label>
          <input type="text" id="inp" placeholder="First name">
        </span>
        <span class="right1">
          <label>First name</label>
          <input type="text" id="inp" placeholder="Last name">
        </span><br/>
      </div>
      <div>
        <p class="email">Email</p>
        <input type="email" id="email2" placeholder="Your email address">
      </div>
      <div>
        <p class="passw">Password</p>
        <input type="password" id="pass" placeholder="Choose password">
      </div>
      <div class="checktext"><input id="check" type="checkbox">&nbsp;&nbsp;<span class="txt2">By continuing I certify that i am 18 years of age, and i agree to the <a href="#">User Agreement</a> and <a href="#">Privacy Policy</a>. </span><br/><div class="sgn">
			<button>Create Account</button></div></div>
  </div>
<div class="already">Already have a Coinbase account? <a href="#">Log in</a></div>
</div>
</template>

<script>
export default {
  name: 'Signup',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-wrap {
  width: 98.7vw;
  height: 930px;
  background-color: rgb(6, 103, 208);
  font-family:'DM Sans', sans-serif;
}
nav {
  padding: 0px;
  margin-top: -40px;
}
ul {
  padding: 0px;
}
li {
  margin: 0px;
  list-style-type: none;
  display: inline-block;
}
.coinbase {
  font-size: 34px;
  margin-left: 120px;
}
.dropdown {
  position: relative;
  border-color: transparent;
  background-color: rgb(6, 103, 208);
  color: white;
  margin-left: 355px;
  margin-right: 18px;
   outline: none;
   display: inline-block;
}
.dropdown-content {
  display: none;
  position: fixed;
  background-color: white;
  width: 820px;
  height: 65vh;
  left: 220px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  border-bottom: 1px solid #dddddd;
}
.dropdown:hover .dropdown-content {display: block;}
.dropdown-content a:hover {background-color: #ddd;}
.dropdown2 {
  position: relative;
  display: inline-block;
  border-color: transparent;
  background-color: rgb(6, 103, 208);
  color: white;
  margin-left: 18px;
  outline: none;
}
.dropdown2-content {
  display: none;
  position: fixed;
  background-color: #f1f1f1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.dropdown2-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}
.dropdown2:hover .dropdown2-content {display: block;}
.dropdown2-content a:hover {background-color: #ddd;}
.prices {
  margin: 5px;
}
.coinbase {
  color: rgb(255, 255, 255);
}
.dropbtn {
  color: rgb(255, 255, 255);
}
.prices,a {
  color: rgb(255, 255, 255);
  position: relative;
  cursor: pointer;
  font-size: 14px;
  font-weight: 500;
  text-decoration: none;
  transition: all 150ms ease 0s;
}
.sign-in {
 margin-left: 220px; 
}
.sign-in,a {
  color: rgb(255, 255, 255);
  text-decoration: none;
  transition: all 150ms ease 0s;
}
.signup {
  margin-left: 30px;
  position: relative;
  width: 80px;
  color: rgb(255, 255, 255);
  cursor: pointer;
  font-size: 14px;
  background-color: transparent;
  border-radius: 4px;
  transition: all 80ms ease-in-out 0s;
  padding: 12px 20px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(255, 255, 255);
  border-image: initial;
}
.left {

    float: left;
    margin-left: 10px;
    margin-top: 10px;
  
}
.right {
  
    float: right;
    margin-top: 10px;
    margin-right: 10px;
}
dd {
    color: rgb(131, 143, 160);
    display: block;
    font-weight: 400;
    height: 15px;
    line-height: 15.6px;
    margin-left: 0px;
}
dl {
    padding: 2px;
    margin-top: 50px;
}
dt {
    color: rgb(5, 15, 25);
    display: block;
    font-size: 17px;
    font-weight: 500;
    height: 23px;
    line-height: 23px;
    margin-block-end: 12px;
    margin-bottom: 6px;
    margin-top: 0px;
}
.p1 {
    font-size: 48px;
    font-weight: 600;
    font-style: normal;
    line-height: 1.17;
    color: white;
    text-align: center;
    margin-top: 0px;
}
.p2{
  opacity: 0.9;
  font-size: 16px;
  font-weight: normal;
  line-height: 1.75;
  color: rgb(255, 255, 255);
  margin: 24px 0px;
  text-align: center;
  margin-top: -25px;
}
.products:hover .dropdown-content {display: block;}
 .p3 {
   position: absolute;
   font-size: 14px;
    font-weight: 500;
    text-transform: uppercase;
    color: rgba(17, 51, 83, 0.6);
    margin-top: 20px;
    margin-left: 18px;
    margin-bottom: 0px;
    margin-right: 20px;
 }
img {
  padding: 2px;
  margin-top: 35px;
 }
 .createtxt {
    margin-bottom: 40px;
    height: 34px;
    font-size: 30px;
    font-weight: 400;
    line-height: 1.13;
    text-align: center;
    color: rgb(255, 255, 255);
 }
.createbox {
  position: absolute;
  width: 500px;
  height: 560px;
  margin-left: 450px;
  background-color: white;
}
.left1 {
  float:left;
  margin-left: 27px;
}
.right1 {
  float:right;
   margin-right: 23px;
  }
label {
  color: rgb(5, 15, 25);
  cursor: default;
  display: block;
  font-size: 14px;
  font-weight: 400;
  height: 16px;
  line-height: 12px;
  margin-top: 25px;
}
#inp{
  color: rgb(5, 15, 25);
  line-height: 23px;
  font-size: 16px;
  margin-top: 4px;
  padding: 10px;
  height: 45px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(236, 239, 241);
  border-radius: 4px;
  background: none;
}
#email2{
  position: absolute;
    color: rgb(5, 15, 25);
  line-height: 23px;
  font-size: 16px;
  width: 430px;
  left: 30px;
  height: 45px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(236, 239, 241);
  border-radius: 4px;
  background: none;
  top: 170px;
  padding: 10px;
}
.email {
  position: absolute;
  color: rgb(5, 15, 25);
  cursor: default;
  display: block;
  font-size: 14px;
  font-weight: 400;
  height: 16px;
  line-height: 12px;
  margin-top: 132px;
  margin-left: 30px;
}
.passw {
    position: absolute;
  color: rgb(5, 15, 25);
  cursor: default;
  display: block;
  font-size: 14px;
  font-weight: 400;
  height: 16px;
  line-height: 12px;
  margin-top: 256px;
  margin-left: 30px;
}
#pass{
  position: absolute;
    color: rgb(5, 15, 25);
  line-height: 23px;
  font-size: 16px;
  width: 430px;
  left: 30px;
  height: 45px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(236, 239, 241);
  border-radius: 4px;
  background: none;
  top: 295px;
  padding: 10px;
}
button {
  position: absolute;
 background-color: rgb(22, 82, 240);
border-bottom-color: rgb(22, 82, 240);
border-bottom-left-radius: 4px;
border-bottom-right-radius: 4px;
border-bottom-style: solid;
border-bottom-width: 1px;
border-image-outset: 0px;
border-image-repeat: stretch;
border-image-slice: 100%;
border-image-source: none;
border-image-width: 1;
border-left-color: rgb(22, 82, 240);
border-left-style: solid;
border-left-width: 1px;
border-right-color: rgb(22, 82, 240);
border-right-style: solid;
border-right-width: 1px;
border-top-color: rgb(22, 82, 240);
border-top-left-radius: 4px;
border-top-right-radius: 4px;
border-top-style: solid;
border-top-width: 1px;
box-sizing: border-box;
color: rgb(255, 255, 255);
cursor: pointer;
display: inline-block;
font-size: 18px;
font-stretch: 100%;
font-weight: 500;
height: 72px;
letter-spacing: normal;
line-height: 20.7px;
margin-bottom: 0px;
margin-left: -25px;
margin-right: 0px;
margin-top: 20px;
padding-bottom: 25px;
padding-left: 35px;
padding-right: 35px;
padding-top: 25px;
text-align: center;
width: 432px;
}
.checktext {
  position: absolute;
  color: rgb(72, 76, 87);
  cursor: pointer;
  display: block;
  font-size: 14px;
  font-weight: 500;
  height: 20px;
  line-height: 20px;
  margin-bottom: 5px;
  margin-left: -180px;
  min-height: 20px;
  padding-left: 0px;
  padding-top: 10px;
  color: rgb(5, 15, 25);
  cursor: default;
  display: inline;
  top: 380px;
  width: 390px;
}
#check {
  position: absolute;
  margin-left: -10px;
  padding: 10px
}
.checktext a {
  text-decoration: none;
  color: blue;
}
.already {
  position: absolute;
      font-size: 16px;
    font-weight: 500;
    text-align: center;
    color: rgb(255, 255, 255);
    top: 800px;
    margin-left: 550px;
}
</style>
