<template>
  <header>
    <h1>Anshul Kadyan</h1>
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/projects">Projects</router-link>
      <router-link to="/contact">Contact</router-link>
    </nav>
  </header>
</template>

<style scoped>
/* Add styling for the header */
header {
  background-color: #3498db;
  padding: 0px;
  color: white;
}

/* Style the h1 tag */
h1 {
  margin: 0;
}

/* Style the navigation links */
nav {
  margin-top: 10px;
}

router-link {
  margin-right: 15px;
  text-decoration: none;
  color: white;
  font-weight: bold;
  font-size: 16px;
}

router-link:hover {
  text-decoration: underline;
}
</style>
