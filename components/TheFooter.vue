<template>
<div class="footer-wrap">

  <div class="footer-container">
    <div>
      <NuxtLink to="/home">Как заказать питание </NuxtLink>
      <NuxtLink to="/home">Специальное питание для тебя </NuxtLink>
      <NuxtLink to="/home">Способы оплаты </NuxtLink>

    </div>
    <div>
      <NuxtLink to="/home">О нас </NuxtLink>
      <NuxtLink to="/home">Контакты </NuxtLink>
      <NuxtLink to="/home">Новости</NuxtLink>
    </div>
    <div>
      <NuxtLink to="/home"> </NuxtLink>
      <NuxtLink to="/home">Рецепты </NuxtLink>
      <NuxtLink to="/home">Доставка еды</NuxtLink>
    </div>

  </div>
  <div class="footer-container-info "> Все права защищены 2022</div>

</div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>

.footer-wrap{
    background-color: #e3f2fd;
    padding: 20px;
}

.footer-container{
  display: flex;

}
.footer-container > div {
  width: calc(100%/3) ;
  display: inline-grid;
  padding:0 10px 0 10px;
}
</style>
