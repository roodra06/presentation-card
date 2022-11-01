<template>
  <div>
    <div class="card targeta" style="width: 18rem;">
      <img class="card-img-top" src="../assets/futbol.png" alt="Card image cap">
      <div class="card-body">
        <h5 class="card-title">Football</h5>
        <p class="card-text">I like play football, I play everyday at the night</p>
      </div>
    </div>
    <div class="card targeta" style="width: 18rem;">
      <img class="card-img-top" src="../assets/basket.png" alt="Card image cap">
      <div class="card-body">
        <h5 class="card-title">Basketball</h5>
        <p class="card-text">I like play basketball, I play everyday at the night</p>
      </div>
    </div>
    <div class="card targeta" style="width: 18rem;">
      <img class="card-img-top" src="../assets/natacion.png" alt="Card image cap">
      <div class="card-body">
        <h5 class="card-title">Swimming</h5>
        <p class="card-text">I like to Swimming, I going to swimming all weekends</p>
      </div>
    </div>
    <div class="card targeta" style="width: 18rem;">
      <img class="card-img-top" src="../assets/sing.png" alt="Card image cap">
      <div class="card-body">
        <h5 class="card-title">Sing</h5>
        <p class="card-text">I like sing but I fell i'm not the best, but I try to be better.</p>
      </div>
    </div>
    <div class="card targeta" style="width: 18rem;">
      <img class="card-img-top" src="../assets/couple.png" alt="Card image cap">
      <div class="card-body">
        <h5 class="card-title">Be with my Girl</h5>
        <p class="card-text">I love to be with my girlfriend but we don't have enought time</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Likes',
};
</script>

<style scoped>
.targeta {
  display: inline-block;
  background: #2c3e50;
  color: white;
  height: 30em;
  margin-bottom: 200px;
}
</style>
