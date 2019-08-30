<template>
  <div class="main-wrap">
    	<span class="left">
            <h1>$150B+</h1>
            <div id="p2">Cryptocurrency exchanged</div>
		</span>
        <span class="middle">
            <h1>102</h1>
            <div id="p2">Countries supported</div>
		</span>
        <span class="right">
            <h1>30M+</h1>
            <div id="p2">Customers served</div>
		</span>
  </div>
</template>

<script>
export default {
  name: 'Crypto',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-wrap {
    position: absolute;
    width: 98.7vw;
    height: 33vh;
    background-color: rgb(6, 103, 208);
}
h1 {
    color: rgb(255, 255, 255);
    display: block;
    font-size: 56px;
    font-weight: 500;
    height: 48px;
    line-height: 48px;
    margin-block-end: 12px;
    margin-block-start: 0px;
    margin-bottom: 12px;
    margin-inline-end: 0px;
    margin-inline-start: 0px;
    margin-left: 0px;
    margin-right: 0px;
    margin-top: 0px;
    text-align: center;
}
#p2 {
    color: rgb(255, 255, 255);
    display: block;
    font-size: 16px;
    font-weight: 400;
    height: 24px;
    line-height: 24px;
    opacity: 0.7;
    text-align: center;
}
.left {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 70px;
    margin-left: 190px;
}
.middle {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 70px;
    margin-left: 540px;
}
.right {
    position: absolute;
    width: 285px;
    height: 357px;
    text-align: center;
    margin-top: 70px;
    margin-left: 895px
}
</style>
