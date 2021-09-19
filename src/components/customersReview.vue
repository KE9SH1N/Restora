<template>
    <div>
        <!-- review section starts  -->

<section class="review" id="review">

    <h1 class="heading"> our customers <span>reviews</span> </h1>

    <div class="box-container">

        <div class="box">
            <img src="../assets/images/pic1.png" alt="">
            <h3>john deo</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="far fa-star"></i>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti delectus, ducimus facere quod ratione vel laboriosam? Est, maxime rem. Itaque.</p>
        </div>
        <div class="box">
            <img src="../assets/images/pic2.png" alt="">
            <h3>john deo</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="far fa-star"></i>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti delectus, ducimus facere quod ratione vel laboriosam? Est, maxime rem. Itaque.</p>
        </div>
        <div class="box">
            <img src="../assets/images/pic3.png" alt="">
            <h3>john deo</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="far fa-star"></i>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti delectus, ducimus facere quod ratione vel laboriosam? Est, maxime rem. Itaque.</p>
        </div>

    </div>

</section>

<!-- review section ends -->
    </div>
</template>
<script>
export default {
    
}
</script>
<style scroped>
    /* review section starts */

.review .box-container{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
}

.review .box-container .box{
  text-align: center;
  padding:2rem;
  border:1rem solid #fff;
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.3);
  border-radius: .5rem;
  flex:1 1 30rem;
  background:#333;
  margin-top: 6rem;
}

.review .box-container .box img{
  height: 12rem;
  width:12rem;
  border-radius: 50%;
  border:1rem solid #fff;
  margin-top: -8rem;
  object-fit: cover;
}

.review .box-container .box h3{
  font-size: 2.5rem;
  color:#fff;
  padding:.5rem 0;
}

.review .box-container .box .stars i{
  font-size: 2rem;
  color:var(--red);
  padding:.5rem 0;
}

.review .box-container .box p{
  font-size: 1.5rem;
  color:#eee;
  padding:1rem 0;
}

/* review section ends */
</style>