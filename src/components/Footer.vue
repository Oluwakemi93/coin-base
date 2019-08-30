<template>
  <div class="main-wrap">
    <footer class="row">
		<div class="column">
			<div>
			  <h3 class="coinbase">coinbase</h3>
        <a href="tel:+2348099872932" class="addr">+2348099872932</a><br/>
			  <a href="mailto:raimioluwakemi@yahoo.com" class="addr">raimioluwakemi@yahoo.com</a><br>
			  <p>&copy; 2019 Coinbase</p>
			</div>
		</div>
		<div class="column">
      <ul>
        <h5>Products</h5>
        <li><a href="#">Coinbase</a></li>
        <li><a href="#">Commerce</a></li>
        <li><a href="#">Custody</a></li>
        <li><a href="#">Earn</a></li>
        <li><a href="#">Pro</a></li>
        <li><a href="#">USD Coin</a></li>
        <li><a href="#">Wallet</a></li>
        <li><a href="#">Ventures</a></li>
      </ul> 
		</div>
		<div class="column">
      <ul>
        <h5>Learn</h5>
        <li><a href="#">Buy Bitcoin</a></li>
        <li><a href="#">Buy Bitcoin Cash</a></li>
        <li><a href="#">Buy Ethereum</a></li>
        <li><a href="#">Buy Litecoin</a></li>
        <li><a href="#">Buy XRP</a></li>
        <li><a href="#">Supported countries</a></li>
        <li><a href="#">Status</a></li>
        <li><a href="#">Taxes</a></li>
      </ul> 
		</div>
		<div class="column">
				<ul>
          <h5>Company</h5>
				  <li><a href="#">About</a></li>
					<li><a href="#">Affliates</a></li>
					<li><a href="#">Careers</a></li>
					<li><a href="#">Partners</a></li>
					<li><a href="#">Press</a></li>
					<li><a href="#">Open Source</a></li>
					<li><a href="#">Legal & Privacy</a></li>
					<li><a href="#">Support</a></li>
				</ul> 
		</div>
		<div class="column">
				<ul>
          <h5>Social</h5>
					<li><a href="#">Blog</a></li>
					<li><a href="#">Twitter</a></li>
					<li><a href="#">Facebook</a></li>
				</ul> 
		</div>
	</footer>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped>
.main-wrap {
  position: absolute;
  width: 99vw;
  height: 50vh;
  background: rgb(255, 255, 255);
  margin: 70px;
  margin-left: 120px;
}
.column {
  float: left;
  width: 15%;
  padding: 10px;
  height: 300px;
  text-align: justify;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
li {
  background-color: rgba(0, 0, 0, 0);
  color: rgb(17, 51, 85);
  cursor: pointer;
  display: block;
  font-size: 16px;
  font-weight: 400;
  line-height: 28px;
  opacity: 0.7;
  height: 28px;
  opacity: 0.7;
}
h5 {
  color: rgb(17, 51, 85);
  display: block;
  font-size: 16px;
  font-weight: 500;
  height: 18px;
  line-height: 18.4px;
  margin-block-end: 20px;
  margin-block-start: 5px;
  margin-bottom: 20px;
  margin-inline-end: 0px;
  margin-inline-start: 0px;
  margin-top: 5px;
}
.coinbase {
  color: rgb(22, 82, 240);
  font-weight: 800;
  font-size: 20px;
  line-height: 18.4px;
}
p {
  color: rgb(17, 51, 85);
  display: block;
  font-size: 16px;
  font-weight: 400;
  height: 28px;
  line-height: 28px;
  margin-top: 28px;
  opacity: 0.7;
  text-decoration-color: rgb(17, 51, 85);
  text-decoration-line: none;
  text-decoration-style: solid;
  text-size-adjust: 100%;
  width: 198.656px;
}
a {
  text-decoration: none;
}
.addr {
    background-color: rgba(0, 0, 0, 0);
  color: rgb(17, 51, 85);
}
</style>
