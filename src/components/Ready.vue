<template>
  <div class="main-wrap">
    	<span class="left">
            <h1>Ready to buy bitcoin?</h1>
            <p id="p2">Get started with NGN 50 or less.</p>
		</span>
        <span class="right">
    <div>
        <span>
            <input type="email" placeholder="Email Address">
        </span>
        <span>
            <button class="green">Get Started</button>
        </span>
    </div>
		</span>
  </div>
</template>

<script>
export default {
  name: 'Ready',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-wrap {
    position: absolute;
    width: 98.7vw;
    height: 50vh;
    background-color: rgb(3, 49, 99);
}
h1 {
    color: rgb(255, 255, 255);
    display: block;
    font-size: 43px;
    font-weight: 650;
    height: 36px;
    line-height: 36.8px;
    margin-block-end: 0px;
    margin-block-start: 0px;
    margin-bottom: 0px;
    margin-inline-end: 0px;
    margin-inline-start: 0px;
    margin-left: 0px;
    margin-right: 0px;
    margin-top: 0px;
    text-align: justify;
}
#p2 {
    color: rgb(255, 255, 255);
    display: block;
    font-size: 43px;
    font-weight: 400;
    height: 36px;
    line-height: 36.8px;
    margin-block-end: 0px;
    margin-block-start: 0px;
    margin-bottom: 0px;
    margin-inline-end: 0px;
    margin-inline-start: 0px;
    margin-left: 0px;
    margin-right: 0px;
    margin-top: 15px;
    text-align: center;
}
.left {
    position: absolute;
    float: left;
    height: 357px;
    text-align: justify;
    margin-top: 120px;
    margin-left: 120px;
}
.right {
    position: absolute;
    float: right;
    height: 357px;
    text-align: center;
    margin-top: 140px;
    margin-left: 805px;
}
input {
    margin-right: 10px;
    font-family: Graphik, sans-serif;
    font-size: 16px;
    font-weight: normal;
    line-height: 1.75;
    color: rgb(11, 52, 102);
    flex: 1 1 0%;
    padding: 13px 16px 15px;
    border-radius: 4px;
    border-width: initial;
    border-style: none;
    border-color: initial;
    border-image: initial;
    width: 255px;
    height: 40px;
}
.green {
    position: relative;
    width: auto;
    color: rgb(255, 255, 255);
    cursor: pointer;
    font-size: 16px;
    background-color: rgb(5, 177, 105);
    margin: 0px;
    border-radius: 4px;
    transition: all 80ms ease-in-out 0s;
    padding: 24px;
    border-width: 1px;
    border-style: solid;
    border-color: rgb(5, 177, 105);
    border-image: initial;
    margin-left: 2px;
}
</style>
