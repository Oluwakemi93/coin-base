<template>
  <div class="main-wrap">
   <p class="p1">Buy and sell cryptocurrency</p>
  <p class="p2">Coinbase is the easiest place to buy, sell, and manage your cryptocurrency portfolio.</p>
  <div class="email1">
	<span>
		<input type="email" placeholder="Email Address">
	</span>
	<span>
		<button class="green">Get Started</button>
	</span>
</div>

  </div>
</template>

<script>
export default {
  name: 'Coinbase',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-wrap {
  font-family: 'DM Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  position:absolute;
  color:#fff;
  margin:-8px 0px 0px -8px;
  width: 98.7vw;
  height: 65vh;
  background-color: rgb(6, 103, 208);
}
.p1 {
    font-size: 48px;
    font-weight: 600;
    font-style: normal;
    line-height: 1.17;
    color: white;
    text-align: center;
    margin: 30px 0px 0px 2px;
}
.p2{
  opacity: 0.9;
  font-size: 15px;
  font-weight: normal;
  line-height: 1.75;
  color: rgb(255, 255, 255);
  text-align: center;
  margin-top: 21px;
  margin-right: 17px;
}
input {
    -webkit-appearance: none;
    font-family: Graphik, sans-serif;
    font-size: 16px;
    font-weight: normal;
    line-height: 28px;
    color: rgb(11, 52, 102);
    flex: 1 1 0%;
    padding: 13px 16px 15px;
    border-radius: 4px;
    border-width: initial;
    border-style: none;
    border-color: initial;
    border-image: initial;
    display: inline-block;
    margin-left: 458px;
    margin-top: 20px;
    width: 250px;
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
    margin-left: 10px;
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
</style>
