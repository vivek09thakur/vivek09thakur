<script lang="ts">
  import ProjectContainer from './lib/ProjectContainer.svelte'
</script>

<main>
    <h1>My Current Ongoing Projects</h1>

    <div class="card">
      <ProjectContainer />
    </div>
</main>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap');
  *{
    font-family: 'Roboto Mono', monospace;
  }
  main{
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    height: 100%;
    width: 100%;
    margin: 0 auto;
  }
  h1{
    font-size: 2rem;
    margin-top: 1rem;
    padding: 0;
    font-weight: 400;
  }
</style>