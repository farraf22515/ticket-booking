<template>
  <footer>
    <div class="footer-content">
      <p>&copy; 2023 Your Name. All rights reserved.</p>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>
.footer-content {
  text-align: center;
  padding: 1rem;
  background-color: #f8f9fa;
}

.footer-content nav ul {
  list-style: none;
  padding: 0;
}

.footer-content nav ul li {
  display: inline;
  margin: 0 10px;
}

.footer-content nav ul li a {
  text-decoration: none;
  color: #007bff;
}
</style>