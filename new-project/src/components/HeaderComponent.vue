<template>
    <header>
        
        <nav>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
        </nav>
      </header>
</template>

<script>
export default {
    name: 'HeaderComponent'
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