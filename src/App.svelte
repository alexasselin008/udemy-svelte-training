<script>
  let name = "Alex";
  let age = 30;

  function incrementAge() {
    age += 1;
  }
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}, i am {age} years old!</h1>
<button on:click={incrementAge}>Change Age</button>
