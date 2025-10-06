<template>
  <section id="projects">
    <h2>My Projects</h2>
    <div class="project-list">
      <ProjectCard 
        v-for="project in projects" 
        :key="project.id" 
        :title="project.title" 
        :description="project.description" 
        :link="project.link" 
      />
    </div>
  </section>
</template>

<script>
import ProjectCard from './ProjectCard.vue';

export default {
  name: 'Projects',
  components: {
    ProjectCard
  },
  data() {
    return {
      projects: [
        {
          id: 1,
          title: 'Project One',
          description: 'Description of project one.',
          link: 'https://link-to-project-one.com'
        },
        {
          id: 2,
          title: 'Project Two',
          description: 'Description of project two.',
          link: 'https://link-to-project-two.com'
        },
        {
          id: 3,
          title: 'Project Three',
          description: 'Description of project three.',
          link: 'https://link-to-project-three.com'
        }
      ]
    };
  }
};
</script>

<style scoped>
.project-list {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}
</style>