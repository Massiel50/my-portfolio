<template>
  <mdb-card class="card-body skillCardBody" >
    <mdb-card-title>
      <h2>SKILLS</h2>
      </mdb-card-title>
    <mdb-card-text></mdb-card-text>
    <div class="flex-row">
      <p>2 rows of icons and skill descripton below</p>
      <mdb-icon icon="laptop-code" />
      
      <mdb-icon icon="palette" />
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
.skillCardBody {
  background-color: black;
  color:blanchedalmond;
}

</style>