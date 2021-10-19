<template>
  <mdb-card class="card-body projectsBody" >
      <mdb-card-title>
        <h2>PROJECTS</h2>
      </mdb-card-title>

    <div class="flex-row">
      <div id= "row1">
        <div id= "col1">
        <mdb-view src="https://mdbootstrap.com/img/Photos/Others/forest-sm.jpg" class="hoverable" alt="placeholder">
         <mdb-mask flex-center overlay="teal-strong" text="strong overlay" />
        </mdb-view>
        </div>
        <div id= "col2">
        <mdb-view src="https://mdbootstrap.com/img/Photos/Others/forest-sm.jpg" class="hoverable" alt="placeholder">
         <mdb-mask flex-center overlay="teal-strong" text="strong overlay" />
        </mdb-view>
        </div>
      </div>

    </div>
  </mdb-card>
</template>

<script>
  import { mdbCard, mdbCardTitle,  mdbView, mdbMask } from 'mdbvue';
  export default {
    name: 'Projects',
    components: {
      mdbCard,
      mdbCardTitle,
      mdbView,
      mdbMask
    }
  }
</script>