<template>
  <div class="main-wrap">
    <h1>The most trusted cryptocurrency platform</h1>
    <p>Here are a few reasons why you should choose Coinbase</p>
    	<span class="left">
            <img src="../assets/secure.png">
            <h2>Secure storage</h2>
            <p id="p2">We store the vast majority of the digital assets in secure offline storage.</p>
            <div class="learn"><a href="https://www.coinbase.com/security" title="Learn how Coinbase keeps your funds safe and secure"
            color="textAccent">Learn more &#8250;</a></div>
		</span>
	    <span class="middle">
            <img src="../assets/protected.png">
            <h2>Protected by insurance</h2>
            <p id="p2">Cryptocurrency stored on our servers is covered by our insurance policy.</p>
            <div class="learn"><a href="https://www.coinbase.com/security" title="Learn how Coinbase keeps your funds safe and secure"
            color="textAccent">Learn more &#8250;</a></div>
		</span>
        <span class="right">
            <img src="../assets/industry.png">
            <h2>Industry best practices</h2>
            <p id="p2">Coinbase supports a variety of the most popular digital currencies.</p>
            <div class="learn"><a href="https://www.coinbase.com/security" title="Learn how Coinbase keeps your funds safe and secure"
            color="textAccent">Learn more &#8250;</a></div>
		</span>
  </div>
</template>

<script>
export default {
  name: 'Platform',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-wrap {
    position: absolute;
    width: 98.7vw;
    height: 123vh;
    background: rgb(255, 255, 255);
    color: black;
}
h1 {
    color: rgb(15, 50, 86);
    display: block;
    font-size: 40px;
    font-weight: 500;
    height: 66px;
    line-height: 48px;
    margin-block-end: 21px;
    margin-block-start: 0px;
    margin-bottom: 0px;
    margin-inline-end: 0px;
    margin-inline-start: 0px;
    margin-left: 0px;
    margin-right: 0px;
    margin-top: 0px;
    text-align: center;
}
p {
    color: rgb(144, 161, 184);
    display: block;
    font-family: Graphik, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
    font-size: 18px;
    font-weight: 400;
    height: 20px;
    margin-block-end: 0px;
    margin-block-start: 0px;
    margin-bottom: 0px;
    margin-inline-end: 0px;
    margin-inline-start: 0px;
    margin-left: 0px;
    margin-right: 0px;
    margin-top: 0px;
    text-align: center;
}
.left {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 100px;
    margin-left: 190px;
}
.middle {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 100px;
    margin-left: 540px
}
.right {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 100px;
    margin-left: 895px;
}
h2 {
    margin-top: 72px;
    margin-bottom: 14px;
    font-size: 20px;
    font-weight: 500;
    color: rgb(0, 47, 107);
}
#p2 {
    color: rgb(144, 161, 184);
    line-height: 24px;
    font-size: 16px;
    margin: 14px 0px 23px;
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}
a {
    color: rgb(22, 82, 240);
    cursor: pointer;
    font-size: 14px;
    font-weight: 500;
    text-decoration: none;
    transition: color 0.25s ease 0s;
}
.learn {
    margin-top: 50px;
}
</style>
