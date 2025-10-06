<template>
  <div class="project-card">
    <h3 class="project-title">{{ title }}</h3>
    <p class="project-description">{{ description }}</p>
    <a :href="link" class="project-link" target="_blank">View Project</a>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    },
    link: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
.project-card {
  border: 1px solid #ccc;
  border-radius: 8px;
  padding: 16px;
  margin: 16px 0;
  transition: box-shadow 0.3s;
}

.project-card:hover {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.project-title {
  font-size: 1.5em;
  margin-bottom: 8px;
}

.project-description {
  font-size: 1em;
  margin-bottom: 12px;
}

.project-link {
  color: #007bff;
  text-decoration: none;
}
</style>