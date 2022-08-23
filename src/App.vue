<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

<center>
  <nav>
      <RouterLink to="/profile">Profile</RouterLink>
      <RouterLink to="/skill">Skill</RouterLink>
  </nav>
</center>
     
  <div class="ono">
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
  background-color:aquamarine ;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;

  border-radius: 2rem;
}
header {
  line-height: 1.5;
  max-height: 100vh;
  margin-top: 1rem;
  margin-left: 2rem;
  margin-right: 2rem;
  padding-top: 3rem;

}

.logo {
  display: block;
  margin: 0 auto 2rem;
  margin-top: 1rem;
  border-radius: 2rem;

}

nav {
  width: 80rem;
  font-size: 12px;
  margin-top: 2rem;
  background-color: rgb(255, 255, 255);
  margin-bottom: 2rem;
  
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
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
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
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -2rem;
    font-size: 1rem;
    padding: 1rem 0;
  }
}
</style>
