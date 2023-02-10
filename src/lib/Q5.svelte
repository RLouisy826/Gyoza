<script>
    import Img from '../assets/gyoza3.jpg'
</script>

<div id="wrapper-container">
    <div class="wrapper">
        <div id="img-bck">
            <img src={Img} alt="gyoza3">
        </div>
        <div id="hh-txt">
            <h2>Origin of the recipe ?</h2>
            <p>The origin of gyoza dates back to ancient China, where dumplings filled with various ingredients were a popular food. Over time, the recipe for gyoza has evolved and been refined through the centuries, with different regions developing their own variations and cooking techniques. In Japan, gyoza were introduced after World War II and quickly became popular, with Japanese chefs adding their own unique twists to the recipe. Today, gyoza continue to be a beloved dish, with many variations and styles being enjoyed all over the world.</p>
        </div>
    </div>
</div>
<style>

    #wrapper-container{
        display: block;
        margin-right: auto;
        margin-left: auto;
        width: fit-content;
        padding-top: 40px;
        padding-bottom: 40px;
        padding-left: 40px;
        padding-right: 40px;
        background: rgba(255, 255, 255, 0.81);
        backdrop-filter: blur(10px);
        border-radius: 20px;
        border: 1px solid rgba(255, 255, 255, 0.18);
        box-shadow: 0 8px 25px 0 rgb(19, 19, 19);
    }
    .wrapper{
        display: flex;
        justify-content: space-between;
        width: 1100px;
    }
    .wrapper img {
        width: 350px;
        height: 250px;
        border-radius: 15%;
        box-shadow: 0 10px 40px 0 rgb(19, 19, 19);
    }

    #hh-txt{
        margin-right: auto;
        margin-left: auto;
        color: rgb(0, 0, 0);
        width: 450px;
    }
</style>

