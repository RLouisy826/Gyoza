<script>
    import Img from '../assets/gyoza.jpg'
</script>

<div id="wrapper-container">
    <div class="wrapper">
        <div id="img-bck">
            <img src={Img} alt="gyoza3">
        </div>
        <div id="hh-txt">
            <h2>Why the name<em>"Gyoza"</em>?</h2>
            <p>The word "gyoza" is derived from the Chinese word "jiaozi" which refers to a type of filled dumpling. The dish was introduced to Japan after World War II and the name "gyoza" was adopted to refer to the Japanese version of the dumpling. The word "gyoza" has since become commonly used in Japan and other countries to refer to this type of dumpling.</p>
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
        border-radius: 50px;
        box-shadow: 0 10px 40px 0 rgb(19, 19, 19);
    }
    

    #hh-txt{
        margin-right: auto;
        margin-left: auto;
        color: rgb(0, 0, 0);
        width: 450px;
    }
</style>

