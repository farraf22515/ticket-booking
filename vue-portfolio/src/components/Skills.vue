<template>
  <section id="skills">
    <h2>My Skills</h2>
    <ul>
      <li v-for="skill in skills" :key="skill">{{ skill }}</li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      skills: [
        'JavaScript',
        'Vue.js',
        'HTML & CSS',
        'Node.js',
        'Git & GitHub',
        'Responsive Design',
        'API Integration'
      ]
    };
  }
};
</script>

<style scoped>
#skills {
  padding: 20px;
  background-color: #f9f9f9;
}

h2 {
  font-size: 2em;
  margin-bottom: 10px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  font-size: 1.2em;
  margin: 5px 0;
}
</style>