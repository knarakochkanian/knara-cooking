<template>
  <div class="home-card-grid">
    <div class="card">
      <a href="https://www.youtube.com/shorts/K9jOhMz8f1g" class="btn btn-primary"><img src="https://i.ytimg.com/vi/K9jOhMz8f1g/hq720_2.jpg?sqp=-oaymwEdCJACEOADSFXyq4qpAw8IARUAAIhCcAHAAQbQAQE=&rs=AOn4CLBYCJwEb-GO453lWzK0cs84S7q-cw" class="card-img-top" alt="fish"></a>
      <div class="card-body">
        <h5 class="card-title">Рыба</h5>
        <p class="card-text">Простой способ приготовить рыбку </p>
        <a href="https://www.youtube.com/shorts/K9jOhMz8f1g" class="btn btn-primary">recipes video</a>
      </div>
    </div>
    <div class="card">
      <a href="https://www.youtube.com/shorts/Q8L4WnYKbrM" class="btn btn-primary"><img src="https://i.ytimg.com/vi/Q8L4WnYKbrM/hq720_2.jpg?sqp=-oaymwEdCJgDENAFSFXyq4qpAw8IARUAAIhCcAHAAQbQAQE=&rs=AOn4CLDyobihrxYxFp7_FEVJQrpWWQFxVA" class="card-img-top" alt="fish"></a>
      <div class="card-body">
        <h5 class="card-title">KFC</h5>
        <p class="card-text">крылья 1 кг, соус : 2 яйца , 100 мл. молока, мука 2ст.л. , паприка, острый перец, соль . обвалять в хлопьях и обжарить !!!</p>
        <a href="https://www.youtube.com/shorts/Dlc91D-kk6w" class="btn btn-primary">recipes video</a>
      </div>
    </div>
    <div class="card">
      <a href="https://www.youtube.com/shorts/Q8L4WnYKbrM" class="btn btn-primary"><img src="https://i.ytimg.com/vi/Dlc91D-kk6w/hq720_2.jpg?sqp=-oaymwEdCJgDENAFSFXyq4qpAw8IARUAAIhCcAHAAQbQAQE=&rs=AOn4CLCWxvSN6eHKHUZ-mj1yhUMHrFPxoA" class="card-img-top" alt="fish"></a>
      <div class="card-body">
        <h5 class="card-title">Салат</h5>
        <p class="card-text">смесь зелени, один помидор, один перец , обжарить грудку , соус: соевый соус, сок лимона, масло , соль ,перец , кунжут </p>
        <a href="https://www.youtube.com/shorts/Q8L4WnYKbrM" class="btn btn-primary">recipes video</a>
      </div>
    </div>

    <div class="card">
      <a href="https://www.youtube.com/shorts/K9jOhMz8f1g" class="btn btn-primary"><img src="https://i.ytimg.com/vi/bR8dOCRZxZ8/hq720_2.jpg?sqp=-oaymwEdCJcDENAFSFXyq4qpAw8IARUAAIhCcAHAAQbQAQE=&rs=AOn4CLATNGzhcFXMXWNbQ9NzPPPg7YSRLA" class="card-img-top" alt="fish"></a>
      <div class="card-body">
        <h5 class="card-title">Салат с рукколой </h5>
        <p class="card-text">для соуса 2 ст.л. соевого соуса, пол сока лимона , 3 ст.л. масла растительного , соль перец
          в сам салат входит :
          руккола , авокадо, криветки ( отварить) , кунжут  ( по желанию)</p>
        <a href="https://www.youtube.com/shorts/bR8dOCRZxZ8" class="btn btn-primary">recipes video</a>
      </div>
    </div>
    <div class="card">
      <a href="https://www.youtube.com/shorts/K9jOhMz8f1g" class="btn btn-primary"><img src="https://i.ytimg.com/vi/GScW_3vtAGA/hq720_2.jpg?sqp=-oaymwEdCI4CEOADSFXyq4qpAw8IARUAAIhCcAHAAQbQAQE=&rs=AOn4CLCFJkJwyYWWMk6OcfdkJm_0f9N1Gw" class="card-img-top" alt="fish">
      </a>
      <div class="card-body">
        <h5 class="card-title">Морковь по-корейски</h5>
        <p class="card-text">морковь протереть , добавить соль, уксус, сахар . Масло нагреть, добавить к чесноку и перцу</p>
        <a href="https://www.youtube.com/shorts/GScW_3vtAGA" class="btn btn-primary">recipes video</a>
      </div>
    </div>

  </div>


</template>
<script>
export default {
  name: "HomeSlider"
}
</script>

<style scoped>
.home-card-grid{
  margin-top: 30px;
  margin-bottom: 30px;
  display: grid;
  grid-template-columns: auto auto auto;
  column-gap: 30px;
  row-gap: 30px;
  grid-column-start: 4;
  grid-column-end: 2;
}

</style>
