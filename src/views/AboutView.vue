<template>
  <div class="about">
    <h1>This is an AOS page</h1>
  </div>
  <div class="container">
    <div class="item" data-aos="fade-up">1</div>
    <div class="item" data-aos="fade-down">2</div>
    <div class="item" data-aos="fade-right">3</div>
    <div class="item" data-aos="fade-left">4</div>

    <div class="item" data-aos="zoom-in">5</div>
    <div class="item" data-aos="zoom-out">6</div>

    <div class="item" data-aos="slide-up">7</div>

    <div class="item" data-aos="flip-up">8</div>
    <div class="item" data-aos="flip-down">9</div>
    <div class="item" data-aos="flip-right">10</div>
    <div class="item" data-aos="flip-left">11</div>
  </div>

</template>

<style>
* {
  box-sizing: border-box;
}

.item {
  width: 200px;
  height: 200px;
  margin: 50px auto;
  padding-top: 75px;
  background: #ccc;
  text-align: center;
  color: #FFF;
  font-size: 3em;
}
.container{
  grid-row: span 2;
  grid-column: span 2;
}
@media (min-width: 1024px) {
  .about {
    min-height: 80vh;
    display: flex;
    align-items: center;
  }
}
</style>
