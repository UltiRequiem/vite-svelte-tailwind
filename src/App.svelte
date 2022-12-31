<script>
  let randomNumber = Math.random();

  setInterval(() => {
    randomNumber = Math.random();
  }, 1000);
</script>

<main class="h-screen flex flex-col text-center">
  <h1 class="bg-yellow-300 text-5xl p-5">Random Number! 💪</h1>

  <div class="flex-1 flex">
    <p class="m-auto text-3xl">
      {randomNumber}
    </p>
  </div>

  <footer class="bg-yellow-200 text-3xl p-5">By Eliaz Bobadilla</footer>
</main>
