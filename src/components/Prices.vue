<template>
  <div class="main-wrap">
    <table>
  <tr>
    <th>#</th>
    <th id="name">NAME</th>
    <th>    </th>
    <th id="price">PRICE</th>
    <th>CHANGE</th>
    <th>CHART</th>
    <th>TRADE</th>
  </tr>
  <tr>
    <td id="num">1</td>
    <td><img src="../assets/bitcoin.png" width="35" height="35"></td>
    <td id="name"><span id="name2">Bitcoin</span> &nbsp; <span id="name3">BTC</span> </td>
    <td id="price2">NGN 3,623,730.68</td>
    <td id="change">-5.18%</td>
    <td><img src="../assets/chart.png" width="110" height="40"></td>
    <td><button> Buy</button></td>
  </tr>
  <tr>
    <td id="num">2</td>
    <td><img src="../assets/ethereum.png" width="35" height="35"></td>
    <td id="name"><span id="name2">Ethereum</span> &nbsp; <span id="name3">ETH</span> </td>
    <td id="price2">NGN 75,927.01</td>
    <td id="change">-4.46%</td>
    <td><img src="../assets/chart.png" width="110" height="40"></td>
    <td><button> Buy</button></td>
  </tr>
  <tr>
    <td id="num">3</td>
    <td><img src="../assets/litecoin.png" width="35" height="35"></td>
    <td id="name"><span id="name2">Litecoin</span> &nbsp; <span id="name3">LTC</span> </td>
    <td id="price2">NGN 32,758.07</td>
    <td id="change">-5.15%</td>
    <td><img src="../assets/chart.png" width="110" height="40"></td>
    <td><button> Buy</button></td>
  </tr>
  <tr>
    <td id="num">4</td>
    <td><img src="../assets/bitcash.png" width="35" height="35"></td>
    <td id="name"><span id="name2">Bitcoin Cash</span> &nbsp; <span id="name3">BCH</span> </td>
    <td id="price2">NGN 108,876.43</td>
    <td id="change">-4.14%</td>
    <td><img src="../assets/chart.png" width="110" height="40"></td>
    <td><button> Buy</button></td>
  </tr>
</table>

  </div>
</template>

<script>
export default {
  name: 'Prices',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.main-wrap {
  width: 87vw;
  height: 60vh;
  background: rgb(255, 255, 255);
}
table {
  font-family: arial, sans-serif;
  position:absolute;
  width: 100%;
  color: rgba(17, 51, 83, 0.3);
}
td, th {
  border-bottom: 1px solid #dddddd;
  text-align: left;
  padding: 15px;
}
th {
  font-size: 12px;
  font-weight: 500;
  line-height: 1;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(17, 51, 83, 0.3);
  transition: color 200ms ease-in-out 0s;
}
#price {
  padding-left: 380px;
}
#price2 {
  padding-left: 380px;
  line-height: 1.3;
  color: rgb(5, 15, 25);
  font-size: 18px;
  font-weight: 400;
}
#name {
  padding-left: 10px;
}
button {
  position: relative;
  width: auto;
  color: rgb(255, 255, 255);
  cursor: pointer;
  font-size: 14px;
  background-color: rgb(5, 177, 105);
  margin: 0px;
  border-radius: 4px;
  transition: all 80ms ease-in-out 0s;
  padding: 12px 16px;
  border-width: 1px;
  border-style: solid;
  border-color: rgb(5, 177, 105);
  border-image: initial;
}
#change {
  min-width: 76px;
  margin-right: 20px;
  color: rgb(223, 95, 103);
  text-align: left;
}
#name2 {
  line-height: 1.3;
  color: rgb(5, 15, 25);
  font-size: 18px;
  font-weight: 400;
}
#name3 {
  line-height: 1.3;
  color: rgba(17, 51, 83, 0.6);
  font-size: 18px;
  font-weight: 400;
}
#num {
  line-height: 1.3;
  color: rgba(17, 51, 83, 0.6);
  font-size: 18px;
  font-weight: 400;
}
</style>
