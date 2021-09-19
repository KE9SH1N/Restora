<template>
    <div>
        <!-- scroll top button  -->
        <a href="#home" class="fas fa-angle-up" id="scroll-top"></a>
    </div>
</template>
<script>
// export default {
    
// }

window.onscroll = () =>{

  if(window.scrollY > 60){
    document.querySelector('#scroll-top').classList.add('active');
  }else{
    document.querySelector('#scroll-top').classList.remove('active');
  }

}
</script>


<style scoped>
    /* scroll top section starts here */
#scroll-top{
  position: fixed;
  top:-120%;
  right:2rem;
  padding:.5rem 1.5rem;
  font-size: 4rem;
  background:var(--red);
  color:#fff;
  border-radius: .5rem;
  transition: 1s linear;
  z-index: 1000;
}

#scroll-top.active{
  top:calc(100% - 12rem)
}
/* scroll top section ends here */
</style>