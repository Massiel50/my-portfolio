<template>
  <mdb-navbar color="grey" position= "top" class=" lighten-4 py-4">
    <mdb-navbar-nav nav center>
      <mdb-nav-item>
        <mdb-btn href = "https://www.linkedin.com/in/massiel-escano/" tag="a" size="lg" floating class="btn-li" icon="linkedin-in" fab></mdb-btn>
      </mdb-nav-item>
      <mdb-nav-item>
        <mdb-btn href= "https://github.com/Massiel50" tag="a" size="lg" floating class="btn-git" icon="github" fab></mdb-btn>
      </mdb-nav-item>
    </mdb-navbar-nav>
  </mdb-navbar>
</template>


<script>
  import { mdbNavbar, mdbNavbarNav, mdbBtn} from 'mdbvue';
  export default {
    name: 'NavBar',
    components: {
      mdbNavbar,
      mdbNavbarNav,
      mdbBtn
    }
  }
</script>
 
 
