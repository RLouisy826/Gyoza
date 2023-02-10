<script>
    import Hleft from './Hleft.svelte'
    import Hright from './Hright.svelte'
    import Q3 from './Q3.svelte'
    import Q4 from './Q4.svelte'
    import Q5 from './Q5.svelte'
</script>

<div id="app-display">
  <div id="display-container">
    <Hleft />
    <br>
    <Hright />
    <br>
    <Q3 />
    <br>
    <Q4 />
    <br>
    <Q5 />
  </div>
</div>

  <style>
      #app-display{
        display: flex;
        flex-direction: column;
    }

  </style>