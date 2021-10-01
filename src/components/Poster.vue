<template>
  <div class="poster__container">
    <div class="poster__image">
      <img src="../assets/images/4722410.jpg" alt="" />
      <div class="poster__content">
        <div></div>
        <div>
          <div class="series">Season 1</div>
          <div class="poster__title">The Queen's Gambit</div>
          <div class="poster__btn">
            <button class="btn">
              <img src="../assets/svg/streaming.svg" alt="" />Watch now
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss">
.poster__container {
  margin-top: 0rem;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1.6rem 4rem;
  width: 100%;
  .poster__image {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;

    img {
      width: 100%;
      border-radius: 30px;
    }
  }
  .poster__content {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    position: absolute;
    bottom: 0;
    left: 0;
    height: 100%;
    width: 100%;
    // margin: 2rem 2rem;
    background: rgb(29, 29, 29);
    background: linear-gradient(
      90deg,
      rgb(29, 29, 29) 0%,
      rgba(255, 255, 255, 0) 100%
    );
    border-radius: 30px;
    .series {
      margin: 1rem 3rem;
      color: rgb(180, 180, 180);
      font-family: 'Rubik';
    }
    .poster__title {
      margin-bottom: 2rem;
      margin-left: 3rem;
      color: white;
      font-size: 3rem;
    }
    .poster__btn {
      margin: 3rem 3rem;
      button {
        border: none;
        color: white;
        display: flex;
        padding: 1rem 1.8rem;
        background: #ed2517;
        font-family: 'Rubik';
        line-break: auto;
        border-radius: 10px;
        img {
          margin-right: 0.8rem;
        }
      }
    }
  }
}
</style>
