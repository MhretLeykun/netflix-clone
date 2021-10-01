<template>
  <div class="container"></div>
  <div>
    <Navbar />
    <Poster />
    <Popular />
    <footer>
      <div>Netflix redesign by Mhret M.</div>
      <div>
        <router-link to="/">Portfolio</router-link>
        <router-link to="/">Contact</router-link>
      </div>
    </footer>
  </div>
</template>
<script>
import Navbar from '../components/Navbar.vue';
import Poster from '../components/Poster.vue';
import Popular from '../components/Popular.vue';
export default {
  components: {
    Navbar,
    Poster,
    Popular,
  },
  data() {
    return {};
  },
};
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
body {
  font-family: 'Rubik', sans-serif;
}
.container {
  background: rgba(255, 255, 255, 0.216);
  background-attachment: fixed;
  backdrop-filter: blur(70px);
  border: 1px solid rgba(255, 255, 255, 0.426);
  height: 100vh;
  position: fixed;
  top: 0;
  width: 100%;
  left: 0;
  z-index: -9999;
}
footer {
  width: 100%;
  background: none;
  color: rgb(87, 87, 87);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 1.8rem 0;
  div {
    margin: 0.6rem 0;
  }
  a {
    color: #ed2517;
    text-decoration: none;
    padding: 1.9rem 1rem;
  }
}
</style>
