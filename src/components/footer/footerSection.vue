<template>
    <div>
        <!-- footer section  -->

<section class="footer">

    <div class="share">
        <a href="#" class="btn">facebook</a>
        <a href="#" class="btn">twitter</a>
        <a href="#" class="btn">instagram</a>
        <a href="#" class="btn">pinterest</a>
        <a href="#" class="btn">linkedin</a>
    </div>

    <h1 class="credit"> created by <span> mr. web designer </span> | all rights reserved! </h1>

</section>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    /* footer section starts here */
.footer{
  background:#000;
  text-align: center;
}

.footer .share{
  display: flex;
  gap:1.5rem;
  justify-content: center;
  flex-wrap: wrap;
}

.footer .credit{
  padding:2.5rem 1rem;
  color:#fff;
  font-weight: normal;
  font-size: 2rem;
}

.footer .credit span{
  color:var(--red);
}

/* footer section ends here */
</style>