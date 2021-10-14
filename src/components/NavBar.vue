<template>
<div id= "nav">
  <mdb-navbar id ="navCss" color="grey" position= "top" class=" lighten-4 py-4">
    <mdb-navbar-nav nav center>
      <mdb-nav-item>
         <button type="button" class="btn btn-primary btn-lg btn-floating" href= "https://www.linkedin.com/in/massiel-escano/">
         <i class="fab fa-linkedin-in"></i></button>
      </mdb-nav-item>
      <mdb-nav-item>
        <button type="button" size= "fa-5x" class="btn btn-dark btn-lg btn-floating" href= "https://github.com/Massiel50">
         <i class="fab fa-github"></i></button>
      </mdb-nav-item>
    </mdb-navbar-nav>
  </mdb-navbar>
</div>
</template>


<script>
  import { mdbNavbar, mdbNavbarNav, } from 'mdbvue';
  export default {
    name: 'NavBar',
    components: {
      mdbNavbar,
      mdbNavbarNav
    }
  }
</script>
 
 <style>
 #navCss {
  /* padding: 0; */
  background-color: lightgrey;
}

 </style>
