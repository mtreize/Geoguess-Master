<template>
  <div class="footer">
    <v-container>
      <v-row
        class="mt-8"
        justify="center"
      >
        <span id="copyright">Fork du projet Geoguess-Master, dispo sur le github de <strong>Spider Hand</strong>. Merci à lui.</span>
      </v-row>
      <v-row 
        class="mt-2"
        justify="center"
      >

      </v-row>
    </v-container>
  </div>
</template>

<script lang="ts">
import { defineComponent, } from '@vue/composition-api'

export default defineComponent({

})
</script>

<style scoped>
span {
  color: #FFFFFF;
}

.footer {
  position: absolute;
  left: 0;
  top: 1500px;
  bottom: 0;
  padding: 12px;
  height: 210px;
  width: 100%;
  background-color: #061422;
}

.footer-content {
  padding: 12px;
}

#copyright, #credit {
  font-size: 12px;
  color: #7D7D7D;
}

@media (max-width: 450px) {
  .footer {
    top: 1440px;
    height: 300px;
  }
}
</style>