<template>
  <div>
    <!-- header section starts  -->

    <header>
      <a href="#" class="logo"><i class="fas fa-utensils"></i>Restora</a>

      <div id="menu-bar" class="fas fa-bars"></div>

      <nav class="navbar">
        <a href="#home">home</a>
        <a href="#speciality">speciality</a>
        <a href="#popular">popular</a>
        <a href="#gallery">gallery</a>
        <a href="#review">review</a>
        <a href="#order">order</a>
      </nav>
    </header>

    <!-- header section ends -->
  </div>
</template>

<script>
// export default {

// }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scroped>
header {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: #fff;
  padding: 2rem 9%;
  box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.1);
}

header .logo {
  font-size: 2.5rem;
  font-weight: bolder;
  color: #666;
}

header .logo i {
  padding-right: 0.5rem;
  color: var(--red);
}

header .navbar a {
  font-size: 2rem;
  margin-left: 2rem;
  color: #666;
}

header .navbar a:hover {
  color: var(--red);
}

#menu-bar {
  font-size: 3rem;
  cursor: pointer;
  color: #666;
  border: 0.1rem solid #666;
  border-radius: 0.3rem;
  padding: 0.5rem 1.5rem;
  display: none;
}

/* responsive media query section */



@media(max-width:991px){

  header{
    padding:2rem;
  }
 

}



@media(max-width:768px){

  #menu-bar{
    display: initial;
  }

  header .navbar{
    position: absolute;
    top:100%; left: 0; right:0;
    background: #f7f7f7;
    border-top: .1rem solid rgba(0,0,0,.1);
    clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
  }

  header .navbar.active{
    clip-path: polygon(0 0, 100% 0, 100% 100%, 0% 100%);
  }

  header .navbar a{
    margin: 1.5rem;
    padding:1.5rem;
    display: block;
    border:.2rem solid rgba(0,0,0,.1);
    border-left:.5rem solid var(--red);
    background:#fff;
  }

}
</style>
