<template lang="">
    <div>
        <!-- home section starts  -->

        <section class="home" id="home">

            <div class="content">
                <h3>food made with love</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptas accusamus tempore temporibus rem amet laudantium animi optio voluptatum. Natus obcaecati unde porro nostrum ipsam itaque impedit incidunt rem quisquam eos!</p>
                <a href="#" class="btn">order now</a>
            </div>

            <div class="image">
                <img src="../assets/images/home-img.png" alt="">
            </div>

        </section>

        <!-- home section ends -->
    </div>
</template>


<script>
export default {};
</script>


<style>

/* home content */
.home{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
  min-height: 100vh;
  align-items: center;
  /* background:url(../images/home-bg.jpg) no-repeat; */
  background-size: cover;
  background-position: center;
}

.home .content{
  flex:1 1 40rem;
  padding-top: 6.5rem;
}

.home .image{
  flex:1 1 40rem;
}

.home .image img{
  width:100%;
  padding:1rem;
  animation:float 3s linear infinite;
}

@keyframes float{
  0%, 100%{
    transform: translateY(0rem);
  }
  50%{
    transform: translateY(3rem);
  }
}

.home .content h3{
  font-size: 5rem;
  color:#333;
}

.home .content p{
  font-size: 1.7rem;
  color:#666;
  padding:1rem 0;
}

/* home contents ends */
</style>

