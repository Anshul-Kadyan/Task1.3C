<template>
  <section>
    <h2>Projects</h2>
    <div v-for="project in projects" :key="project.id">
      <h3>{{ project.title }}</h3>
      <a :href="project.link" target="_blank">{{ project.description }}</a>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          id: 1,
          title: "Pokemon Website",
          description: "This is my Task1.1P",
          link: "https://github.com/Anshul-Kadyan/Task1.1P",
        },
        {
          id: 2,
          title: "TODO APP",
          description: "This is my Task2.1P",
          link: "https://github.com/Anshul-Kadyan/Task2.1C",
        },
        {
          id: 3,
          title: "CSS3 Perspective Playground Video",
          description: "This is my Task2.2P",
          link: "https://github.com/Anshul-Kadyan/Task2.2C",
        },
        {
          id: 4,
          title: "Vue Concept Elobration Website",
          description: "This is my Task2.3P",
          link: "https://github.com/Anshul-Kadyan/Task2.3C",
        },
        {
          id: 5,
          title: "JavaScript Website",
          description: "This is my Task1.2P",
          link: "https://github.com/Anshul-Kadyan/Task2.1",
        },
      ],
    };
  },
};
</script>

<style scoped>
a {
  text-decoration: none;
}
</style>
