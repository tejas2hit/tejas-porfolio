<template>
  <div class="container pt-4">
    <div class="card">
      <h4 class="card-header">Hello There <a href="#" class="cursor">👋</a></h4>
      <div class="card-body bg-light pb-1">
        <h5 class="row">
          <div class="col-7">
            I'm Tejas Bargal,

            <h5 class="card-text mt-3">
              a passionate developer who loves to learn and build stuff.
            </h5>
          </div>
          <div class="col text-right">
            <a href="mailto:tejas.bargal88@gmail.com" class="btn btn-primary m-2">
              <font-awesome-icon
                :icon="['fas', 'envelope']"
                size="lg"
                class="icon-size"
              />
            </a>
            <a href="https://github.com/tejas2hit" class="btn btn-dark m-2">
              <font-awesome-icon
                :icon="['fab', 'github']"
                size="lg"
                class="icon-size"
              />
            </a>
            <a
              href="https://www.linkedin.com/in/tejas-b-b3181284"
              class="btn btn-primary m-2"
            >
              <font-awesome-icon
                :icon="['fab', 'linkedin']"
                size="lg"
                class="icon-size"
              />
            </a>
          </div>
        </h5>
      </div>
    </div>
  </div>
</template>
  
  <script>
export default {
  name: "main-info",
};
</script>
  
<style scoped>
.icon-size {
  font-size: 35pt;
}
.cursor {
  text-decoration: none;
  cursor: grab;
}
</style>