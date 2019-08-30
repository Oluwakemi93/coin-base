<template>
  <div class="main-wrap">
    <h1>Get started in a few minutes</h1>
    <p>Coinbase supports a variety of the most popular digital currencies.</p>
    	<span class="left">
            <img src="../assets/create.png">
            <h2>Create an account</h2>
		</span>
	    <span class="middle">
            <hr/>
            <img src="../assets/link.png">
            <h2>Link your bank account</h2>
		</span>
        <span class="right">
            <hr/>
            <img src="../assets/started.png">
            <h2>Start buying & Selling</h2>
		</span>
  </div>
</template>

<script>
export default {
  name: 'Started',
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
    height: 48px;
    line-height: 48px;
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
p {
    color: rgb(4, 49, 105);
    display: block;
    font-size: 16px;
    font-weight: 400;
    height: 28px;
    line-height: 28px;
    margin-block-end: 10.72px;
    margin-block-start: 14px;
    margin-bottom: 10.72px;
    margin-inline-end: 0px;
    margin-inline-start: 0px;
    margin-left: 0px;
    margin-right: 0px;
    margin-top: 14px;
    opacity: 0.7;
    text-align: center;
}
hr {
    position: absolute;
    color: rgb(0, 0, 0);
    flex-direction: row;
    font-weight: 400;
    line-height: 18.4px;
    margin-top: 40px;
    margin-left: -120px;
    width: 135px;
}
.left {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 60px;
    margin-left: 190px
}
.middle {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 60px;
    margin-left: 540px
}
.right {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 60px;
    margin-left: 895px
}
h2 {
    color: rgb(35, 49, 67);
    display: block;
    font-size: 20px;
    font-weight: 500;
    height: 46px;
    line-height: 23px;
    margin-block-end: 20px;
    margin-block-start: 30px;
    margin-bottom: 20px;
    margin-inline-end: 0px;
    margin-inline-start: 0px;
    margin-left: 0px;
    margin-right: 0px;
    margin-top: 30px;
    text-align: center;
}
</style>
