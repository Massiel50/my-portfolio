<template>
  <mdb-card class="card-body" >
    <mdb-card-title>
      <p>No <br> THIS IS</p>
      </mdb-card-title>
    <mdb-card-text></mdb-card-text>
    <div class="flex-row">
      <a>M@SSI</a>
    </div>
  </mdb-card>
</template>

<script>
  import { mdbCard, mdbCardTitle, mdbCardText } from 'mdbvue';
  export default {
    name: 'About',
    components: {
      mdbCard,
      mdbCardTitle,
      mdbCardText
    }
  }
</script>

<style>
.card-body{
 width: 75%; 
 margin-top: 1rem;
 font-size: 4rem;
 float: left;
}

p {
  font-size: 2rem;
}
</style>