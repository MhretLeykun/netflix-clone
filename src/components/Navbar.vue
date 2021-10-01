<template>
  <div class="navbar__container">
    <div class="navbar__content">
      <div class="navbar__logo">
        <img src="../assets/svg/netflix.svg" alt="" />
      </div>
      <div class="navbar__links">
        <div>
          <router-link class="active" to="/">New</router-link>
        </div>
        <div>
          <router-link to="/">Movies</router-link>
        </div>
        <div>
          <router-link to="/">Series</router-link>
        </div>
        <div>
          <router-link to="/">Cartoons</router-link>
        </div>
      </div>
    </div>
    <div class="navbar__icons">
      <div>
        <router-link to="/"
          ><img src="../assets/svg/search-interface-symbol.svg" alt=""
        /></router-link>
      </div>
      <div>
        <router-link to="/"
          ><img src="../assets/svg/bell(3).svg" alt=""
        /></router-link>
      </div>
    </div>
  </div>
</template>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
body {
  font-family: 'Rubik', sans-serif;
}
.navbar__container {
  width: 100vw;
  background: transparent;
  display: flex;
  justify-content: space-between;
  padding: 1.8rem 4rem;
  .navbar__content {
    display: flex;
    align-items: center;
    justify-content: center;
    .navbar__logo {
      width: 120px;
    }
    .navbar__links {
      display: flex;
      margin-bottom: 0.3rem;
      margin-left: 1.8rem;
      a {
        margin: 0 1.8rem;
        font-size: 0.9rem;
        color: rgb(87, 87, 87);
        text-decoration: none;
        &.active {
          color: #ed2517;
        }
      }
    }
  }
  .navbar__icons {
    display: flex;
    align-items: center;
    justify-content: center;
    a {
      img {
        width: 20px;
        margin: 0 0.8rem;
      }
    }
  }
}
</style>
