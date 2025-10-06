<template>
  <header>
    <h1 class="site-title">My Portfolio</h1>
    <nav>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
.site-title {
  font-size: 2rem;
  margin: 0;
}

nav {
  margin-top: 1rem;
}

.nav-links {
  list-style: none;
  padding: 0;
}

.nav-links li {
  display: inline;
  margin-right: 1rem;
}

.nav-links a {
  text-decoration: none;
  color: #333;
}
</style>