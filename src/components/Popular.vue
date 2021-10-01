<template>
  <div class="popular__container">
    <div class="popular__title">
      <p>Popular on Netflix</p>
    </div>
    <div class="movies">
      <div class="movie__container">
        <div class="movie__image">
          <img src="../assets/images/25485.jpg" alt="" />
        </div>
        <div class="movie__detail">
          <div class="rating">
            <div>
              <img src="../assets/svg/star.svg" alt="" /> <span>9.2</span>
            </div>
            <span class="season">8 Seasons </span>
          </div>
          <p>Game Of Thrones</p>
        </div>
      </div>
      <div class="movie__container">
        <div class="movie__image">
          <img
            src="../assets/images/wp6581266-money-heist-2020-4k-wallpapers.jpg"
            alt=""
          />
        </div>
        <div class="movie__detail">
          <div class="rating">
            <div>
              <img src="../assets/svg/star.svg" alt="" /> <span>9.0</span>
            </div>
            <span class="season">4 Seasons </span>
          </div>
          <p>Money Heist</p>
        </div>
      </div>
      <div class="movie__container">
        <div class="movie__image">
          <img src="../assets/images/1902849.jpg" alt="" />
        </div>
        <div class="movie__detail">
          <div class="rating">
            <div>
              <img src="../assets/svg/star.svg" alt="" /> <span>8.4</span>
            </div>
            <span class="season">4 Seasons </span>
          </div>
          <p>The Crown</p>
        </div>
      </div>

      <div class="movie__container">
        <div class="movie__image">
          <img
            src="../assets/images/wp1915192-the-blacklist-wallpapers.jpg"
            alt=""
          />
        </div>
        <div class="movie__detail">
          <div class="rating">
            <div>
              <img src="../assets/svg/star.svg" alt="" /> <span>8.1</span>
            </div>
            <span class="season">8 Seasons </span>
          </div>
          <p>The Blacklist</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.popular__container {
  padding: 0rem 4rem;
  .popular__title {
    font-size: 2rem;
    // font-weight: bold;
    margin-top: 1rem;
    margin-bottom: 1rem;
  }
  .movies {
    display: flex;
    justify-content: space-between;
  }
  .movie__container {
    width: 300px;
    padding: 0.8rem;
    background: white;
    border-radius: 20px;
    margin: 2rem 0;
    .movie__image {
      img {
        border-radius: 14px;
        width: 100%;
      }
    }
    .movie__detail {
      margin: 1rem 0;
      .rating {
        display: flex;
        align-items: center;
        // justify-content: center;
        img {
          width: 15px;
          margin-right: 0.2rem;
        }
        div {
          padding: 0.3rem;
          border: 1.5px solid #ffc107;
          border-radius: 10px;
        }
        .season {
          color: #5e5e5e;
          margin-left: 01.2rem;
        }
      }
      p {
        margin-top: 1rem;
        font-size: 1rem;
      }
    }
  }
}
</style>
