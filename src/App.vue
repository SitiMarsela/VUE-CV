<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

<nav></nav>

 

     
<div class="ono">
   <nav>
      <RouterLink to="/profile">Profile</RouterLink>
      <RouterLink to="/skill">Skill</RouterLink>
  </nav>
  <header>
  <img alt="Vue logo" class="logo" src="@/assets/potosela.jpg" width="190" height="250" />
    <div class="wrapper">
      <HelloWorld msg="Siti Marsela" />
    </div>
  </header>
  <RouterView />

</div>

     
</template>

<style scoped>
.ono{
  background-color:rgb(255, 255, 255) ;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
  border-radius: 2rem;
  
}
header {
  line-height: 1.5;
  max-height: 100vh;
  /* margin-top: 1rem; */
  margin-left: 2rem;
  margin-right: 2rem;

}

h1{
  padding-left: 3rem;
  padding-top: 3rem;
}

h5{
  padding-top: 8rem;
  padding-left: 3rem;
}
.logo {
  display: block;
  border-radius: 2rem;
  padding-top: -50px;
}

nav {
  width: 80rem;
  font-size: 12px;
  /* margin-top: 2rem; */
  /* background-color: rgb(255, 255, 255); */
  /* margin-bottom: 2rem; */
  /* padding-left: 5rem; */
  
}

nav a.router-link-exact-active {
  color: var(--color-text);
  color: black;
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 2rem 0 2rem;
  border-left: 1px solid var(--color-border);
  padding-left: 5rem;
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
    padding-top: -50px;
  }

  header .wrapper {
    margin-top: 50px;
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
    color: rgb(18, 60, 73);
  }

  nav {
    text-align: left;
    /* margin-left: -2rem; */
    font-size: 1rem;
    padding: 1rem 0;
  }
}
</style>
