<script lang="ts">
  import ProjectContainer from "./lib/ProjectContainer.svelte";
  import Nav from "./lib/Nav.svelte";
  import SideNav from "./lib/_sideNav.svelte";
</script>

<main>
  <!-- Navbar -->
  <Nav />
  <!-- Sidebar -->
  <SideNav />
  <!-- Project-Container -->
  <div class="container">
    <ProjectContainer />
  </div>
</main>

<style lang="css3">
  @import url("https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap");
  * {
    font-family: "Roboto Mono", monospace;
  }
  main {
    height: 100%;
    width: 100%;
    margin: 0 auto;
  }
  .container {
    margin: 0 auto;
  }
</style>
