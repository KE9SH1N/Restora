<template>
    <div>
        <!-- steps section starts  -->

<div class="step-container">

    <h1 class="heading">how it <span>works</span></h1>

    <section class="steps">

        <div class="box">
            <img src="../assets/images/step-1.jpg" alt="">
            <h3>choose your favorite food</h3>
        </div>
        <div class="box">
            <img src="../assets/images/step-2.jpg" alt="">
            <h3>free and fast delivery</h3>
        </div>
        <div class="box">
            <img src="../assets/images/step-3.jpg" alt="">
            <h3>easy payments methods</h3>
        </div>
        <div class="box">
            <img src="../assets/images/step-4.jpg" alt="">
            <h3>and finally, enjoy your food</h3>
        </div>
    
    </section>

</div>

<!-- steps section ends -->
    </div>
</template>



<script>
export default {
    
}
</script>



<style>
    /* how it works section */
.steps{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
  padding:1rem;
}

.steps .box{
  flex:1 1 25rem;
  padding:1rem;
  text-align: center;
}

.steps .box img{
  border-radius: 50%;
  border:1rem solid #fff;
  box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);
}

.steps .box h3{
  font-size: 3rem;
  color:#333;
  padding:1rem;
}

.gallery .box-container{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
}
/* how its works ends */
</style>