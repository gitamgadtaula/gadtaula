<template>
  <div>
    <div class="main">
      <div>
        <h1>Gadtaula Group</h1>
        <h3>We talk about startups that people like!</h3>
      </div>
    </div>
    <div class="about-us">
      <img src="@/assets/images/logo.png" />
      <div class="about-title">
        <h1>Who are we?</h1>
        <h2>
          We are enthusiastically driven group of people working rigorously for
          the development of startup ideas that we believe will ease human lives
        </h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
}
.main {
  background-image: url("@/assets/images/hero-bg.png");
  height: 100vh;
  width: 100%;
  padding: 20px;
  display: flex;
  justify-content: flex-end;
  background-attachment: fixed;
  align-items: center;
}
h1,
h2 {
  /* color: #3d2348; */
  font-weight: 1000;
  padding: 4px 0px;
}
.about-us {
  padding: 20px;
  background-color: #f9fafb;
  background-image: url("@/assets/images/ill.svg");
  background-repeat: no-repeat;
  /* background-size: cover; */
  background-position: right;
}

.about-title {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
</style>
