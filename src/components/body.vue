<template>
  <div class="body-grid">
      <img width="300px" src="https://cdn.wallpapersafari.com/20/14/0N4Ik7.jpg" alt="Squidward">
    <p>"You like Krabby Patties, don't you Squidward..."</p>
    <img width="300px"  src="https://i.pinimg.com/originals/b4/02/19/b40219b0e854f67221479a0d89909f84.jpg" alt="Spongebob" >
    <div id="sidePanel">
      <new-sponge> </new-sponge>
    </div>
  </div>
  
  
</template>

<script>
import NewSponge from "./sidepanel.vue";
export default {
  name: "page-body",
  components: {
    NewSponge
  }
};
</script>

<style scoped>
    .body-grid {
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-rows: 1fr 1fr 1fr 2fr;
    }
</style>