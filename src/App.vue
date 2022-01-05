
<script>
import Sidebar from '@/components/sidebar/Sidebar'
import { sidebarWidth } from '@/components/sidebar/state'
export default {
  components: { Sidebar },
  setup() {
    return { sidebarWidth }
  }
}
</script>
<template>
  <Sidebar />
  <div :style="{ 'margin-left': sidebarWidth }">
    <router-view />

  <footer>
    <div class="footer1">
<a href="https://61d482940327745607ae8534--gamemeet.netlify.app/?fbclid=IwAR2mIY_Y3C7FReT3TvyizcacckQf6eQDL-kdOJsju7UKRNWQE9ievaUNgg8">Forside</a>
<a href="https://nifty-montalcini-3382e1.netlify.app/">Log ind</a>
<a href="https://nifty-montalcini-3382e1.netlify.app/">Kontakt</a>
 <img class="logos" src="./assets/yty.png" width="40px" height="40px">
 <img class="logos" src="./assets/skzjx.png" width="40px" height="40px">
 <img class="logos" src="./assets/sjzk.png" width="50px" height="45px">
<a href="https://nifty-montalcini-3382e1.netlify.app/">Regler</a>
<a href="https://nifty-montalcini-3382e1.netlify.app/">Om os</a>
     </div>
    </footer>
  </div>
  <div id="app">
        <img class="logo" src="./assets/Gamemeet.png">
    </div>

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;600;700&display=swap');

#app {
  font-family: 'Nunito', sans-serif;
  text-align: center;
  color: #ffffff;
}





body {background-color: black} 

.logo {
position: absolute;
width: 180px;
height: 90px;
left: -2px;
top: 10px;

}

.footer1 {
  flex-direction: row;
  display: flex;
  white-space: initial;
  justify-content: space-between;
  padding-bottom: 10px;
}

a { text-decoration: none; color:aliceblue}



.footer3 {
  color: white;
}


#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
