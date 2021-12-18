<template>
  <div class="entry-container mb-3 pointer"
  @click="$router.push({name: 'entry', params: {id: 10}})"
  >
      <!-- Titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="fs-5 mx-1">Dic</span>
            <span class="mx-2 fw-light">2021</span>
        </div>

        <div class="entry-description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, impedit unde incidunt nulla soluta mollitia repellat nesciunt, itaque officia vero voluptates exercitationem ratione necessitatibus nam obcaecati culpa labore laboriosam in!
        </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .entry-container{
        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;

        &:hover{
            background-color: lighten($color: grey, $amount: 45);
            transition: 0.2s all ease-in;
        }
        
    }
</style>