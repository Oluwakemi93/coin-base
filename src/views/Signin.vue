<template>
  <div class="main-wrap">
    <nav id="navbar">
      <ul>
        <li class="coinbase"><h6>Coinbase</h6></li>
        <li><div class="dropdown"><p class="dropbtn">Products &nbsp;<i class="fa fa-caret-down"></i></p>
          <div class="dropdown-content">
            <a href="#">Buy/Sell Digital Currency</a>
            <a href="#">Coinbase Pro &nbsp;<i class="fa fa-external-link"></i></a>
            <a href="#">Coinbase Prime &nbsp;<i class="fa fa-external-link"></i></a>
            <a href="#">Developer Platform &nbsp;<i class="fa fa-external-link"></i></a> 
            <a href="#">Coinbase Commerce &nbsp;<i class="fa fa-external-link"></i></a> 	
          </div>
        </div>
        </li>
        <li class="help"><a href="#">Help</a></li>
        <li class="prices"><a href="#">Prices</a></li>
        <li class="sign-in"><a href="#">Sign In</a></li>
        <li class="signup">Sign Up</li>
      </ul>
	</nav>
	<h2>Sign in to Coinbase</h2>
	<div class="signbox">
		<input id="email" type="email" placeholder="Email"><br/>
		<input id="email" type="email" placeholder="Password">
		<div class="checktext"><input id="check" type="checkbox"><span class="txt2">Keep me signed in on this computer</span><span class="sgn">
			<button>SIGN IN</button></span></div>
	</div>
    <p class="textlink"><a href="#">Forgot password?</a> · <a href="#">Don't have an account? </a>· <a href="#">Privacy Policy</a><br/>
<a href="#">Have an issue with 2-factor authentication?</a></p>
  </div>
</template>

<script>
export default {
  name: 'Signin',
}
</script>

<style scoped>
.main-wrap {
  height: 100vh;
  background-color: rgb(6, 103, 208);
  font-family: "DM sans", sans-serif;
  margin: 40px -8px 4px -8px;
}
nav {
  padding: 0px;
  margin-top: -40px;
}
ul {
  padding: 5px;
}
li {
  margin: 8px;
  list-style-type: none;
  display: inline-block;
}
.coinbase {
  font-size: 34px;
  margin-left: 70px;
  margin-top: -55px;
  color: white;
}
.dropdown {
  position: relative;
  border-color: transparent;
  background-color: rgb(6, 103, 208);
  color: white;
  margin-left: 750px;
  margin-right: 18px;
  outline: none;
  display: inline-block;
}
.dropdown-content {
  position: absolute;
  display: none;
  position: fixed;
  background-color: white;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  line-height: 6px;
}
.dropdown-content a {
  color: black;
  padding: 12px 20px;
  text-decoration: none;
  display: block;
  font-size: 12px;
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

.prices,a {
  color: rgb(255, 255, 255);
  cursor: pointer;
  font-size: 14px;
  font-weight: 500;
  text-decoration: none;
  transition: all 150ms ease 0s;
}
.sign-in,a {
  color: rgb(255, 255, 255);
  text-decoration: none;
  transition: all 150ms ease 0s;
}
.signup {
  position: relative;
  width: 45px;
  color: rgb(255, 255, 255);
  cursor: pointer;
  font-size: 12px;
  background-color: transparent;
  border-radius: 1px;
  transition: all 80ms ease-in-out 0s;
  padding: 12px 10px;
  border-width: 2px;
  border-style: solid;
  border-color: rgb(255, 255, 255);
  border-image: initial;
}
h2 {
    margin-bottom: 40px;
    height: 34px;
    font-size: 30px;
    font-weight: 400;
    line-height: 1.13;
    text-align: center;
    color: #fff;
}
.signbox {
  width: 370px;
  height: 200px;
  margin-left: 480px;
  background: rgb(255, 255, 255);
  color: black;
  padding: 10px;
}
#email {
    -webkit-appearance: none;
    font-family: Graphik, sans-serif;
    font-size: 16px;
    font-weight: normal;
    line-height: 28px;
    color: rgb(11, 52, 102);
    flex: 1 1 0%;
    padding: 13px 16px 15px;
    border: 1px solid #b1dfb1;
    border-radius: 4px;
    margin-left: 10px;
    margin-top: 20px;
    width: 300px;
    height: 10px;
}
button {
  width: 95px;
  color: white;
  background-color: rgb(6, 103, 208);
  cursor: pointer;
  font-size: 14px;
  border-radius: 4px;
  padding: 12px 20px;
  border-width: 1px;
  border-style: solid;
  margin-left: 27px;
}
.checktext {
  color: rgb(72, 76, 87);
  cursor: pointer;
  display: block;
  font-size: 12px;
  font-weight: 500;
  height: 20px;
  line-height: 20px;
  margin-bottom: 5px;
  min-height: 20px;
  padding-left: 20px;
  padding-top: 10px;
}
#check {
  margin-left: -10px;
}
.textlink {
    text-align: center;
    font-size: 15px;
    color: #fff!important;
}
.textlink a {
  cursor: pointer;
  display: inline;
  font-size: 15px;
  line-height: 21px;
  text-align: center;
  text-decoration-color: rgb(255, 255, 255);
  text-decoration-line: none;
  text-decoration-style: solid;
  text-size-adjust: 100%;
}
i {
  float: right;
}
</style>
