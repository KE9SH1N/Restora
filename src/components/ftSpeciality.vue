<template>
    <div>
        <!-- speciality section starts  -->

<section class="speciality" id="speciality">

    <h1 class="heading"> our <span>speciality</span> </h1>

    <div class="box-container">

        <div class="box">
            <img class="image" src="../assets/images/s-img-1.jpg" alt="">
            <div class="content">
                <img src="../assets/images/s-1.png" alt="">
                <h3>tasty burger</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda inventore neque amet ipsa tenetur voluptates aperiam tempore libero labore aut.</p>
            </div>
        </div>
        <div class="box">
            <img class="image" src="../assets/images/s-img-2.jpg" alt="">
            <div class="content">
                <img src="../assets/images/s-2.png" alt="">
                <h3>tasty pizza</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda inventore neque amet ipsa tenetur voluptates aperiam tempore libero labore aut.</p>
            </div>
        </div>
        <div class="box">
            <img class="image" src="../assets/images/s-img-3.jpg" alt="">
            <div class="content">
                <img src="../assets/images/s-3.png" alt="">
                <h3>cold ice-cream</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda inventore neque amet ipsa tenetur voluptates aperiam tempore libero labore aut.</p>
            </div>
        </div>
        <div class="box">
            <img class="image" src="../assets/images/s-img-4.jpg" alt="">
            <div class="content">
                <img src="../assets/images/s-4.png" alt="">
                <h3>cold drinks</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda inventore neque amet ipsa tenetur voluptates aperiam tempore libero labore aut.</p>
            </div>
        </div>
        <div class="box">
            <img class="image" src="../assets/images/s-img-5.jpg" alt="">
            <div class="content">
                <img src="../assets/images/s-5.png" alt="">
                <h3>tasty sweets</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda inventore neque amet ipsa tenetur voluptates aperiam tempore libero labore aut.</p>
            </div>
        </div>
        <div class="box">
            <img class="image" src="../assets/images/s-img-6.jpg" alt="">
            <div class="content">
                <img src="../assets/images/s-6.png" alt="">
                <h3>healty breakfast</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda inventore neque amet ipsa tenetur voluptates aperiam tempore libero labore aut.</p>
            </div>
        </div>

    </div>

</section>
    </div>
</template>







<script>
export default {
    
}
</script>








<style>

/* speciality contents starts */
.speciality .box-container{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
}

.speciality .box-container .box{
  flex:1 1 30rem;
  position: relative;
  overflow: hidden;
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);
  border:.1rem solid rgba(0,0,0,.3);
  cursor: pointer;
  border-radius: .5rem;
}

.speciality .box-container .box .image{
  height:100%;
  width:100%;
  object-fit: cover;
  position: absolute;
  top:-100%; left:0;
}

.speciality .box-container .box .content{
  text-align: center;
  background:#fff;
  padding:2rem;
}

.speciality .box-container .box .content img{
  margin:1.5rem 0;
}

.speciality .box-container .box .content h3{
  font-size: 2.5rem;
  color:#333;
}

.speciality .box-container .box .content p{
  font-size: 1.6rem;
  color:#666;
  padding:1rem 0;
}

.speciality .box-container .box:hover .image{
  top:0;
}

.speciality .box-container .box:hover .content{
  transform: translateY(100%);
}

/* speciality contents ends */
    
</style>