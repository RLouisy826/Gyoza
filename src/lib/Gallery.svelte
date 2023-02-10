<script>
  import item1 from '../assets/gyoza1.png'
  import item2 from '../assets/gyoza.jpg'
  import item3 from '../assets/gyoza2.png'
  import item4 from '../assets/gyoza2.jpg'
  import item5 from '../assets/gyoza3.png'
  import item6 from '../assets/gyoza3.jpg'
  import item7 from '../assets/gyoza4.png'
  import item8 from '../assets/gyoza4.jpg'
  import item9 from '../assets/gyoza5.jpg'
</script>
<div class="grid">
    <div class="grid-item"><img src={item5} alt="gyoza_img"></div>
    <div class="grid-item"><img src={item1} alt="gyoza_img"></div>
    <div class="grid-item"><img src={item7} alt="gyoza_img"></div>
    <div class="grid-item"><img src={item4} alt="gyoza_img"></div>
    <div class="grid-item"><img src={item3} alt="gyoza_img"></div>
    <div class="grid-item"><img src={item6} alt="gyoza_img"></div>
    <div class="grid-item"><img src={item2} alt="gyoza_img"></div>
    <div class="grid-item"><img src={item8} alt="gyoza_img"></div>
    <div class="grid-item"><img src={item9} alt="gyoza_img"></div>
</div>



<style>
  *{
    color: white;
  }

  .grid {
  display: grid;
  grid-template-columns: auto auto auto;
  padding: 10px;
  border-radius: 15px;
  background-color: rgba(255, 255, 255, 0.5);
  border: 1px solid rgba(0, 0, 0, 0.3);
}
.grid-item {
  padding: 20px;
  font-size: 30px;
  text-align: center;
}

.grid-item img{
  width: 300px;
  height: 250px;
  border-radius: 15px;
}
</style>