<template>
  <mdb-card class="card-body" >
    <mdb-card-title>
      <h2>SKILLS</h2>
      </mdb-card-title>
    <mdb-card-text></mdb-card-text>
    <div class="flex-row">
      <p>boxes of pics of projects as a link</p>
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