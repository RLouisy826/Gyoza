<script>
    import Home from './Home.svelte'
    import About from './About.svelte'
    import Recipe from './Recipe.svelte'
    export let menuPage = 1;
</script>

<div id="menu">
    <button on:click|preventDefault={() => (menuPage = 1)}>Home</button>
    <button on:click|preventDefault={() => (menuPage = 2)}>About</button>
    <button on:click|preventDefault={() => (menuPage = 3)}>Recipe</button>
</div>
  {#if menuPage === 1}
  <Home />
  {:else if menuPage === 2}
  <About />
  {:else if menuPage === 3}
  <Recipe />
    {:else}
      <h1>
        Page Not Found
      </h1>
  {/if}

  <style>
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

    #menu {
        list-style-type: none;
        display: flex;
        justify-content: space-around;
        margin-left: auto;
        margin-right: auto;
        margin-bottom: 50px;
    }

    button, button:active{
        background: rgb(255, 255, 255);
        padding: 10px 75px;
        border-radius: 25px;
        font-family: 'Ubuntu', sans-serif;
    }

    button:hover{
      background: #651913;
      color: white;
      border-color: #651913;
      animation-name: pulse;
      animation-duration: 0.05s;
      animation-timing-function: ease-in-out;
    }
    
    @keyframes pulse {
      from {
        transform: scale(1);
      }
      to {
        transform: scale(1.2);
      }
    }

  </style>