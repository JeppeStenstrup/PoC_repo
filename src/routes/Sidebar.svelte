<script>
  import { fs } from 'fs';

  fs.readdir('./notexist', function(err, files) {
    if(err) { console.log(err); }

    
  });
</script>

<nav role="navbar">
  <ul>
    <li>1</li>
    <li>2</li>
  </ul>
</nav>

<style>
  nav {
    display: block;
    margin: 0;
    width: 250px;
    background: blue;
  }

  ul {
    display: block;
    height: calc(100vh - 40px);
    margin: 0;
  }
</style>
