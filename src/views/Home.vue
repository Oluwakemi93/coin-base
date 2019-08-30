<template>
  <div id="home">
    <Navbar/>
    <Coinbase id="coinbase"/>
    <Prices id="prices"/>
    <Portfolio id="portfolio"/>
    <Platform id="platform"/>
    <Crypto id="crypto"/>
    <Started id="started"/>
    <Ready id="ready"/>
    <Footer id="footer"/>
    <Navbar id="navbar"/>
    <router-view/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Coinbase from '@/components/Coinbase.vue'
import Prices from '@/components/Prices.vue'
import Portfolio from '@/components/Portfolio.vue'
import Platform from '@/components/Platform.vue'
import Crypto from '@/components/Crypto.vue'
import Started from '@/components/Started.vue'
import Ready from '@/components/Ready.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'home',
  components: {
    Navbar, Coinbase, Prices, Portfolio, Platform, Crypto, Started, Ready, Footer,
  }
}
</script>

<style>
#home {
  width: 100vw;
  font-weight: 200;
  font-family:'DM Sans', sans-serif;
	-webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  color: rgb(255, 255, 255);
  margin-left: -8px;
}
#coinbase {
  position:absolute;
  top: 100px;
  left: 0px;
}
#prices {
  position:absolute;
  top: 355px;
  left: 84px;
}
#portfolio {
  position:absolute;
  top: 750px;
}
#platform {
  position:absolute;
  top: 1650px;
}
#crypto {
  position:absolute;
  top: 2230px;
}
#started {
  position:absolute;
  top: 2530px;
}
#ready {
  position:absolute;
  top: 2910px;
}
#footer {
  position:absolute;
  top: 3237px;
}
</style>
