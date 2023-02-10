<script>
    import gyoza1 from '../assets/gyoza.jpg'
    import bowl from '../assets/bowl.png'
    import spoon from '../assets/spoon.png'
    import serve from '../assets/serve.png'
    import pan from '../assets/pan.png'
    import measurement from '../assets/measurement.png'
    import lid from '../assets/lid.png'
    import repeating from '../assets/repeating.png'
    import heat from '../assets/heat.png'
    import humidity from '../assets/humidity.png'
</script>

<div id="recipe-container">
    <div id="recipe-intro">
        <h2>How to make <em>"Gyoza"</em> ?</h2>
    </div>
    <div id="sub-container">
        <img id="recipe-img" src={gyoza1} alt="recipe-result">
        <div id="recipe-instructions">
            <div id="ingredients">
                <ul>
                    <li>1 package gyoza wrappers (found in Asian grocery stores)</li>
                    <li>1 lb. ground pork</li>
                    <li>1 cup finely shredded cabbage</li>
                    <li>2 green onions, finely chopped</li>
                    <li>2 cloves garlic, minced</li>
                    <li>1 inch ginger, minced</li>
                    <li>1 tbsp. soy sauce</li>
                    <li>1 tsp. sesame oil</li>
                    <li>1 tsp. sake (or rice wine)</li>
                    <li>1 tsp. cornstarch</li>
                    <li>vegetable oil for pan-frying</li>
                </ul>
            </div>
        </div>
    </div>
    <br>
    <hr>
    <br>
    <div id="steps">
        <p><img src={bowl} alt="bowl"/>In a large bowl, mix together the ground pork, shredded cabbage, green onions, garlic, ginger, soy sauce, sesame oil, sake, and cornstarch until well combined.</p>
        <p><img src={spoon} alt="spoon"/>Take a wrapper and place a heaping teaspoon of the filling in the center.</p>
        <p><img src={humidity} alt="humidity"/>Wet the edges of the wrapper with a little water and fold the wrapper in half to form a half-moon shape, sealing the edges.</p> 
        <p><img src={repeating} alt="repeating"/>Repeat with remaining wrappers and filling.</p>
        <p><img src={pan} alt="pan"/>Heat a large skillet over medium heat and add a small amount of oil.</p> 
        <p><img src={heat} alt="heat"/>Once hot, add the gyoza in a single layer, flat-side down. Cook until the bottoms are golden brown, about 2-3 minutes.</p>
        <p><img src={measurement} alt="measurement"/>Add 1/4 cup of water to the skillet, cover, and steam until the filling is cooked through, about 5-7 minutes.</p>
        <p><img src={lid} alt="lid"/>Remove the lid and continue cooking until the water has evaporated and the bottoms are crispy, about 2-3 minutes.</p>
        <p><img src={serve} alt="serve"/>Serve the gyoza hot with a dipping sauce of your choice.</p>
    </div>
</div>

<style>
 #steps img{
    float: left;
    padding-right: 3%;
 }

 #recipe-img{
    width: 600px;
    height: 500px;
 }

    #recipe-container{
        background: rgba(255, 255, 255, 0.81);
        border-radius: 25px;
        padding-left: 15px;
        padding-right: 15px;
        padding-top: 50px;
        padding-bottom: 50px;
        display: block;
    }

    #sub-container{
        display: flex;
        justify-content: space-evenly;
        margin-left: 100px;
        margin-right: 100px;
    }


    #recipe-instructions{
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        width: 600px;
    }

    #steps{
        width: fit-content;
        text-align: start;
        margin-left: 150px;
        margin-right: 100px;
        display: flex;
        flex-direction: column;
    }

    ul{
        list-style-type: none;
        text-align: start;
    }

    #ingredients{
        margin-left: auto;
        margin-right: auto;
    }
</style>