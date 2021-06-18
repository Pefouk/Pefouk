<template>
  <div class="card">
    <a href="#">
      <div class="card-image">
        <img :src="img.src" :alt="img.alt"/>
      </div>
      <div class="card-body">
        <div class="card-date">
          <time>{{ date }}</time>
        </div>
        <div class="card-title">
          <h3>{{ title }}</h3>
        </div>
        <div class="card-excerpt">
          <p>{{ text }}</p>
        </div>
      </div>
    </a>
  </div>

</template>

<script>
export default {
  name: "card",
  props: ['title', 'img', 'text', 'date']
}
</script>

<style scoped lang="scss">
@import "../assets/style.scss";

.card {
  width: 400px;
  border-radius: 25px;
  margin: 10px 10px;
  background-color: floralwhite;
  box-shadow: 0 5px 10px #999;
  transition: 100ms;
  &:hover {
    box-shadow: 0 5px 20px #999;
    transform: scale(1.1);
    filter: grayscale(0);
  }
}

.card a {
  color: #333;
  text-decoration: none;
}

.card-image {
  border-radius: 25px 25px 0 0;
  height: 250px;
  position: relative;
  overflow: hidden;
}

.card-image img {
  width: 100%;
  position: absolute;
  left: 0;
}

.card-body {
  text-align: center;
  padding: 15px 20px;
  box-sizing: border-box;
}

.card-title, .card-excerpt {
}

.card-date, .card-title {
  text-align:center;
  text-transform:uppercase;
  font-weight: bold;
}

.card-date, .card-excerpt {
  color: #777;
}
</style>
