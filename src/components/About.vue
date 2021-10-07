<template>
  <mdb-card class="card-body" style="width: 22rem; margin-top: 1rem;">
    <mdb-card-title>Panel Title</mdb-card-title>
    <mdb-card-text>Some quick example text to build on the panel title and make up the bulk of the panel's content.</mdb-card-text>
    <div class="flex-row">
      <a>Card link</a>
      <a style="margin-left: 1.25rem">Another link</a>
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