<template>
  <div id="app">
    <header>
      <img alt="Vue logo" src="./assets/logo.png">
      <MyTitle></MyTitle>
    </header>

    <main>
      <MyHero></MyHero>
    </main>
    
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import MyHero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyHero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

header{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 50px;
}

header img{
  width: 70px;
  margin-right: 50px;
}



</style>
