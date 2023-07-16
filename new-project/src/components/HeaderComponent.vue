<template>
  <header>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <ButtonComponent></ButtonComponent>
    </nav>
  </header>
</template>

<script>
import ButtonComponent from "./ButtonComponent.vue";


export default {
  name: 'HeaderComponent',
  components: {
    ButtonComponent,
  }
}
</script>

<style>
/* Example CSS styles for the header */
header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

header h1 {
  margin: 0;
}

header nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

header nav ul li {
  display: inline-block;
  margin-right: 10px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
}

header nav ul li a:hover {
  text-decoration: underline;
}
</style>