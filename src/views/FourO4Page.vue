<template>
  <main>
    <div class="error">
      <p>Page not found</p>
      <img src="../assets/images/404-error-dark.png" alt="404 page" />
      <router-link to="/" class="back">Home</router-link>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.error {
  width: 500px;
  box-shadow: 0px 0.2px 0.7px rgba(#e9f0ff, 0.211),
    0px 0.5px 1.5px rgba(#e9f0ff, 0.31), 0px 0.9px 2.6px rgba(#e9f0ff, 0.383),
    0px 1.4px 3.9px rgba(#e9f0ff, 0.444), 0px 2px 5.6px rgba(#e9f0ff, 0.5),
    0px 2.8px 8px rgba(#e9f0ff, 0.556), 0px 4px 11.3px rgba(#e9f0ff, 0.617),
    0px 5.8px 16.4px rgba(#e9f0ff, 0.69), 0px 9px 25.3px rgba(#e9f0ff, 0.789),
    0px 16px 45px rgba(#e9f0ff, 1);
  display: flex;
  flex-direction: column;
  padding: 5em;
  .back {
    background: #e9f0ff;
    padding: 0.7em 1.2em;
    border-radius: 5px;
    font-size: 1.3em;
    text-align: center;
    font-family: "Lato", sans-serif;
    color: #42382b;
    margin-inline: auto;
  }
  img {
    width: 100%;
    object-fit: contain;
  }
  p {
    text-align: center;
    font-family: "Lato", sans-serif;

    color: #92dce5;
    font-size: 1.5rem;
    font-weight: 600;
  }
}
</style>
