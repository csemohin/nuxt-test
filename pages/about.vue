<template>
  <div class="container">
    <div class="row">
      <div class="col-lg-9">
        <h2>About Our Nuxt</h2>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tempore adipisci porro voluptatem expedita incidunt nostrum harum maxime ea vitae architecto!</p>

         <p>Opsum dolor sit amet consectetur adipisicing elit. Tempore adipisci porro voluptatem expedita incidunt nostrum harum </p>
      </div>
      <div class="col-lg-3"></div>
    </div>
  </div>
</template>

<script>
  export default {
    head(){
      return{
        title: 'About Page',
        meta: [
          {name: 'description', content: 'this is description'},
          {keyword: 'keyword', content: 'nuxt, nuxt 2'},
        ]
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>