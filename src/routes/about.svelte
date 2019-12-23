<script>
  function add(a, b) {
    return a + b;
  }

  let result = add(5, 6);
</script>

<svelte:head>
  <title>About</title>
</svelte:head>

<h1>About this site</h1>

<p>This is the 'about' page. There's not much here.</p>

<p>{result}</p>
