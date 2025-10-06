<template>
  <section class="hero">
    <div class="hero-content">
      <h1>Welcome to My Portfolio</h1>
      <p>I'm a passionate developer showcasing my work and skills.</p>
      <router-link to="/projects" class="btn">View Projects</router-link>
    </div>
  </section>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style scoped>
.hero {
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  text-align: center;
}

.hero-content {
  max-width: 600px;
}

.btn {
  padding: 10px 20px;
  background-color: #007bff;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}
</style>
