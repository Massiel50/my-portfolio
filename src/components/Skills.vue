<template>
  <mdb-card class="card-body skillCardBody" >
    <mdb-card-title>
      <h2>SKILLS</h2>
      </mdb-card-title>
    <mdb-card-text></mdb-card-text>
    <div class="flex-row">
      <p>2 rows of icons and skill descripton below</p>
      <div id= "iconRow1">
        <mdb-icon icon="laptop-code" />
      
        <mdb-icon icon="palette" />
      </div>
      
      <div id= "iconRow1">
        <mdb-icon icon="database" />

        <mdb-icon far icon="smile-wink" />
      </div>

    </div>
  </mdb-card>
</template>

<script>
  import { mdbCard, mdbCardTitle, mdbCardText, mdbIcon } from 'mdbvue';
  export default {
    name: 'About',
    components: {
      mdbCard,
      mdbCardTitle,
      mdbCardText,
      mdbIcon
    }
  }
</script>

<style>
.skillCardBody {
  background-color: black;
  color:blanchedalmond;
}

</style>