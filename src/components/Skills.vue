<template>
  <mdb-card class="card-body skillCardBody" >
    <mdb-card-title>
      <h2>SKILLS</h2>
      </mdb-card-title>
    <mdb-card-text></mdb-card-text>
    <div class="flex-row">
      <div id= "iconRow1">
        <mdb-icon icon="laptop-code" />
        <p>Javascript  C#  C++  Node.js  Express</p>
      
        <mdb-icon icon="palette" />
        <p>CSS  React  Vue  Bootstrap  Figma </p>
      </div>
      
      <div id= "iconRow1">
        <mdb-icon icon="database" />
        <p>MySQL  MongoBD  Sequelize</p>

        <mdb-icon far icon="smile-wink" />
        <p>Communication  Time-management</p>
      </div>

    </div>
  </mdb-card>
</template>

<script>
  import { mdbCard, mdbCardTitle, mdbCardText, mdbIcon } from 'mdbvue';
  export default {
    name: 'Skills',
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
p{
  font-size: 15px;
}
</style>