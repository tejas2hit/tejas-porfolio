<template>
  <div class="container">
    <div class="row">
      <div class="col text-right">
        <a
          href="/resume.pdf"
          class="btn btn-danger mb-4"
          download
        >
          Download Pdf
        </a>
      </div>
    </div>

    <img src="../../assets/resume_image.jpg" alt="Resume" />
  </div>
</template>

<script>
export default {
  name: "resume-tab",
};
</script>

<style scoped>
.resume-image {
  background-image: url("../../assets/resume_image.jpg");
}
img {
  width: 100%;
  height: auto;
}
</style>