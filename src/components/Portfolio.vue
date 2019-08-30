<template>
  <div class="main-wrap">
    <h1>Create your cryptocurrency portfolio today</h1>
    <p>Coinbase has a variety of features that make it the best place to start trading</p>
    	<span class="left">
		<table>
			<tr>
				<td><img src="../assets/manage.png"></td>
				<td>
					<dl>
						<dt>Manage your Portfolio</dt>
						<dd>Buy and sell popular digital currencies,</br> keep track of them in the one place.</dd>
					</dl>
				</td>
			</tr>
			<tr>
				<td><img src="../assets/recurring.png"></td>
				<td>
					<dl>
						<dt>Reccurring buys</dt>
						<dd>Invest in cryptocurrency slowly over time<br/> by scheduling buys daily, weekly, or<br/> monthly.</dd>
					</dl>
				</td>
			</tr>
            <tr>
				<td><img src="../assets/vault.png"></td>
				<td>
					<dl>
						<dt>Vault protection</dt>
						<dd>For added security, store your funds in a <br/>vault with time delayed withdrawals.</dd>
					</dl>
				</td>
			</tr>
            <tr>
				<td><img src="../assets/phone.png"></td>
				<td>
					<dl>
						<dt>Mobile apps</dt>
						<dd>Stay on top of the markets with the<br/> Coinbase app for Android or iOS.</dd>
					</dl>
				</td>
			</tr>
		</table>
	</span>
	<span class="right">
		<img src="../assets/portfolio.png" width="700" height="520">
	</span>
  </div>
</template>

<script>
export default {
  name: 'Portfolio',
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
    border-bottom: 1px solid rgb(228, 223, 223);
}
h1 {
    font-size: 40px;
    font-weight: 500;
    color: rgb(15, 50, 86);
    text-align: center;
    margin: 0px 0px 10px;
}
p {
    position: relative;
    color: rgb(144, 161, 184);
    display: block;
    font-weight: 400;
    height: 18px;
    line-height: 18.4px;
    margin-block-end: 16px;
    margin-block-start: 16px;
    margin-inline-end: 0px;
    margin-inline-start: 0px;
    text-align: center;
}
.left {
    float: left;
    width: 45vw;
    margin-left: 110px;
    margin-top: 25px;
}
.right {
    float: right;
    width: 40vw;
    margin-top: -480px;
    margin-right: 240px;
}
dd {
    color: rgb(131, 143, 160);
    display: block;
    font-weight: 400;
    height: 25px;
    line-height: 25.6px;
    width: 564.172px;
    margin-left: 0px;
}
dl {
    padding: 17px;
}
dt {
    color: rgb(0, 0, 0);
    display: block;
    font-size: 20px;
    font-weight: 500;
    height: 23px;
    line-height: 23px;
    margin-block-end: 12px;
    margin-bottom: 12px;
    width: 564.172px;
}
img {
    text-align: justify;
}
</style>
