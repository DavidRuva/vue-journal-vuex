<!-- eslint-disable vue/multi-word-component-names -->
<!-- eslint-disable vue/valid-template-root -->
<template>
  <div
  class="entry-container mb-3 pointer p-2"
  @click="$router.push({ name: 'entry', params: { id:10 }})">
    <div
    class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">06</span>
        <span class="mx-1 fw-light">2021, jueves</span>
    </div>
    <div class="entry-description">
        Ipsum nisi quis ad est officia cillum et. Commodo irure velit reprehenderit non aliquip qui dolor. Deserunt excepteur sint est occaecat aute sunt velit ullamco nulla non ullamco. Excepteur velit ad ipsum dolor deserunt laboris mollit. Aute non adipisicing anim occaecat duis. Dolor veniam minim ex excepteur. Proident cupidatat anim nostrud do nisi dolor in velit officia sint fugiat amet.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2 all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2 all ease-in;
    }
    .entry-description {
        font-size: 12px;
    }
}
</style>