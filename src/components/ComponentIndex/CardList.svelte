<script>
  export let title;
</script>

<style>
  h1 {
    font-family: Overpass;
    font-style: normal;
    font-weight: 600;
    font-size: 27px;
    line-height: 150%;
    margin-bottom: 1rem;
  }
  .grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 25px;
  }
  .list {
    margin-bottom: 5rem;
  }
</style>

<div class="list">
  <h1>{title}</h1>
  <div class="grid">
    <slot />
  </div>
</div>
