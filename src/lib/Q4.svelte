<script>
    import Img from '../assets/gyoza2.jpg'
</script>

<div id="wrapper-container">
    <div class="wrapper">
        <div id="hh-txt">
            <h2>Who eats it ?</h2>
            <p>Gyoza are enjoyed by people of all ages and cultures, both in Japan and worldwide. They are a popular dish in Japanese cuisine and are often served in restaurants and homes. In addition, gyoza have become increasingly popular in other parts of the world, particularly in countries where there are large Asian populations or a growing interest in Asian cuisine.</p>
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

