<template>
  <Femdawgs msg="Femdawgs"/>
</template>

<script>
import Femdawgs from './components/Femdawgs-Web.vue'

export default {
  name: 'App',
  components: {
    Femdawgs
  }
  
}

</script>

<style>


@import url('https://fonts.googleapis.com/css2?family=Amatic+SC&family=Damion&family=Niconne&display=swap');
  
@import url('https://fonts.googleapis.com/css2?family=Bad+Script&display=swap');

/*font-family: 'Amatic SC', cursive;
  font-family: 'Damion', cursive;
  font-family: 'Niconne', cursive;
  font-family: 'Bad Script', cursive;
  */

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin: 0 !important;
  padding: 0 !important;

}

body{
  margin: 0;
}

</style>
