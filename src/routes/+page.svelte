<script>
  import { goto } from "$app/navigation";
</script>

<div class="container">
  <div>
    <p>Please verify that you're a human</p>
    <button on:click={() => goto("https://www.youtube.com/watch?v=dQw4w9WgXcQ")}>
      <img src="/captcha.png" alt="" style="width: 20rem;" />
    </button>
  </div>
</div>

<style>
  .container {
    width: 100svw;
    height: 100svh;

    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>