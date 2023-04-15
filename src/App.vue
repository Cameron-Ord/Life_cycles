<template>
  <div>
    <header id="page_header"><page-header></page-header></header>
    <main id="page_main"><life-cycle></life-cycle></main>
    <footer id="page_footer"><page-footer></page-footer></footer>
  </div>
</template>

<script>

import LifeCycle from './components/LifeCycle.vue';
import PageHeader from './components/PageHeader.vue';
import PageFooter from './components/PageFooter.vue';
export default {
  name: 'life_cycle',
  components: {

   
    PageHeader,
    LifeCycle,
    PageFooter

  }
}
</script>

<style>

*{

  padding: 0px;
  margin: 0px;
}

body{
  font-family: Avenir, Helvetica, Arial, sans-serif;




}
#page_header{

display: grid;

grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

min-height: 10vh;

align-items: center;

justify-items: center;
}

#page_main{

display: grid;

grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

min-height: 80vh;

align-items: center;

justify-items: center;
}

#page_footer{

display: grid;

grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

min-height: 10vh;

align-items: center;

justify-items: center;
}
</style>
