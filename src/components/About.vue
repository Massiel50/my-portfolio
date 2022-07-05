<template>
  <mdb-card class="card-body" >
    <mdb-card-title>
      <p>THIS IS</p>
      <a>M@SSI</a>
      </mdb-card-title>
    <mdb-card-text></mdb-card-text>
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
  margin: auto;
}

p {
  font-size: 2rem;
}
</style>