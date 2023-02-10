<script>
    import Img from '../assets/gyoza5.jpg'
</script>

<div id="wrapper-container">
    <div class="wrapper">
        <div id="hh-txt">
            <h2>Where did it come from ?</h2>
            <p>Gyoza originated in China and were introduced to Japan after World War II. The dish became popular in Japan and has since evolved into a distinct style with its own flavors and cooking techniques. Today, gyoza are widely enjoyed not only in Japan, but also in many other countries around the world.</p>
        </div>
        <div id="img-bck">
            <img src={Img} alt="gyoza4">
        </div>
    </div>
</div>
<style>
    #wrapper-container{
        margin-right: auto;
        margin-left: auto;
        width: fit-content;
    }
    .wrapper{
        display: flex;
        justify-content: space-between;
        width: 1100px;
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

