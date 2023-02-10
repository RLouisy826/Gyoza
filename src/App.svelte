<script>
  import gyo from './assets/preparing-food.svg'
    import Foot from './Foot.svelte';
  import Gyozanav from './lib/Gyozanav.svelte'
</script>

<main>
  <h1 id="main-title">"Gyoza Delight: A Journey Through the World of Japanese Dumplings"</h1>
  <div>
      <img src={gyo} class="logo" alt="Gyoza" />
  </div>
  <Gyozanav/>
  <br>
  <!-- svelte-ignore component-name-lowercase -->
  <br>
</main>
<footer>
  <Foot />
</footer>

<style>

  .logo {
    width: 675px;
    height: 475px;
    padding: 1.5em;
    border-radius: 50px;
    background: white;
    background-size: cover;
    margin-bottom: 50px;
    animation-name: breathing;
    animation-duration: 2s;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
  }

  
  #main-title{
    color: white;
    padding-bottom: 30px;

  }

@keyframes breathing {
  0% {
    box-shadow: 0 7px 20px 5px rgba(0, 0, 0, 0.5333333333);
  }
  50% {
    box-shadow: 0 7px 50px 10px rgb(101, 25, 19, 0.5);
    transform: scale(1.05);
  }
  100% {
    box-shadow: 0 7px 20px 5px rgba(0, 0, 0, 0.5333333333);
  }
}

</style>
