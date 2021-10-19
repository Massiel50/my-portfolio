<template>
  <mdb-card class="card-body" >
    <mdb-card-title>
      <h2>PROJECTS</h2>
      </mdb-card-title>
    <mdb-card-text></mdb-card-text>
    <div class="flex-row">
      <div id= "row1">
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" alt="thumbnail" class="hover"
        style="width: 200px">
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" alt="thumbnail" class="hover"
         style="width: 200px">
      </div>
      
      <div id= "row2">
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" alt="thumbnail" class="hover"
        style="width: 200px">
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" alt="thumbnail" class="hover"
         style="width: 200px">
      </div>

      <div id= "row3">
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" alt="thumbnail" class="hover"
        style="width: 200px">
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" alt="thumbnail" class="hover"
         style="width: 200px">
      </div>

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