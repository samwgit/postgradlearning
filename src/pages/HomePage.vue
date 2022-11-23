<template>

  <div class="card move" style="width: 18rem;">
    <img src="https://thiscatdoesnotexist.com" class="card-img-top" alt="image">
    <div class="card-body">
      <p class="card-text">this website is a fantastic placeholder website if you are learning code.<a
          href="https://thiscatdoesnotexist.com" title="https://thiscatdoesnotexist.com"> Here</a>
      </p>
    </div>
  </div>

</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.move {
  top: 5em;
  right: -43em;
}



.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: 50vw;

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
