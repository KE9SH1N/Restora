<template>
    <div>
        <!-- loader  -->
<div class="loader-container">
    <img src="../assets/images/loader.gif" alt="">
</div>

    </div>
</template>
<script>
// export default {
    
// }
function loader(){
  document.querySelector('.loader-container').classList.add('fade-out');
}

function fadeOut(){
  setInterval(loader, 3000);
}

window.onload = fadeOut();
</script>
<style>
    .loader-container{
  position: fixed;
  top:0; left:0;
  z-index: 10000;
  background:#fff;
  display: flex;
  align-items: center;
  justify-content: center;
  height:100%;
  width:100%;
}

.loader-container.fade-out{
  top:-120%;
}

</style>