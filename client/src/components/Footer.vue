<template>
  <footer>

    <!-- <hr> -->

    <p>© Lucca Rodrigues 2022</p>

    <div class="links">
      <a href="https://github.com/ChromeUniverse/Tank-Battle">GitHub</a>
      •
      <a href="http://34.200.98.64/">Blog</a>
    </div>

  </footer>
  

</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style>

footer {
  font-weight: bold;
  font-size: 1em;
  color: var(--color5);
  padding: 5px;
  opacity: 50%;
}

footer p {
  font-family: 'Recursive';
  margin-bottom: 5px;
}

footer a {
  text-decoration: none;
}

footer a:link {
  color: var(--color4);
}

footer a:visited {
  color: var(--color4);
}

footer a:hover {
  color: var(--color5);
  text-decoration: underline;
  text-decoration-color: var(--color4);
  text-decoration-thickness: 3px;
}

</style>