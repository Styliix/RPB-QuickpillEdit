<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>

    <div class="wrapper">
      
      <button class="button">Reiseziele Juli</button>
      <img class="bgimg" src="src/assets/Paradiesischer-Urlaub.jpg" alt="paradisischer-urlaub">
    </div>
    <div class="wrapper">
    
      <button class="button">Reiseziele August</button>
      <img class="bgimg" src="src/assets/Paradiesischer-Urlaub.jpg" alt="paradisischer-urlaub">
    </div>
    <div class="wrapper">
      
      <button class="button">Reiseziele September</button>
      <img class="bgimg" src="src/assets/Paradiesischer-Urlaub.jpg" alt="paradisischer-urlaub">
    </div>
  </header>

  <main>
    <ThWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

header {
    place-items: center;
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    background-color: black;
    width: 305px;
    height: 175px;
    border-radius: 20px;
    margin-top: 15px;
    margin-left: auto;
    margin-right: auto;
  }

  header .wrapper .button {
    width: 230px;
    height: 40px;
    margin-left: 37px;
    border-radius: 20px;
    background-color: #00ae91;
    border: solid 0px;
    margin-top: 70px;
    font-size: 20px;
    color: white;
    transition: .5s;
    position: absolute;
    z-index: 1;
  }

  .bgimg {
    position: absolute;
    width: 305px;
    height: 175px;
    border-radius: 20px;
    opacity: 0.7;
  }

@media (min-width: 1200px) {
  header {
    display: flex;
    place-items: center;
    
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    float: left;
    background-color: black;
    width: 305px;
    height: 175px;
    border-radius: 20px;
    margin-left: 55px;
  }

  header .wrapper .button {
    width: 230px;
    height: 40px;
    margin-left: 37px;
    border-radius: 20px;
    background-color: #00ae91;
    border: solid 0px;
    margin-top: 70px;
    font-size: 20px;
    color: white;
    transition: .5s;
    position: absolute;
    z-index: 1;
  }

  header .wrapper .button:hover {
    background-color: #00856f;
  }

  .bgimg {
    position: absolute;
    width: 305px;
    height: 175px;
    border-radius: 20px;
    opacity: 0.7;
  }
}

</style>
