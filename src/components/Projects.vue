<template>
  <mdb-card class="card-body" >
    <mdb-card-title>
      <h2>PROJECTS</h2>
      </mdb-card-title>

    <div class="flex-row">
      <div id= "row1">
        <mdb-view>
        <img src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" alt="thumbnail" class="hover"
        style="width: 200px">
        <mdb-mask flex-center overlay="teal-strong" text="strong overlay" />
        </mdb-view>
       <mdb-view class="hoverable overlay" src="https://mdbootstrap.com/img/Others/documentation/img%20(75)-mini.jpg" alt="hoverable">
        <mdb-mask flex-center text="Hover effect" />
        </mdb-view>
      </div>

    </div>
  </mdb-card>
</template>

<script>
  import { mdbCard, mdbCardTitle, mdbMask, mdbView } from 'mdbvue';
  export default {
    name: 'About',
    components: {
      mdbCard,
      mdbCardTitle,
      mdbMask,
      mdbView
    }
  }
</script>