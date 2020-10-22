<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
     <p class="string1">We are a student group acting independently of the University of California. We take full responsibility for our organization and this web site.</p>
    </div>
    <div class="container mx-auto pb-6 flex justify-center">
      <a href="https://www.ocf.berkeley.edu">
      <img src="https://www.ocf.berkeley.edu/hosting-logos/ocf-hosted-penguin.svg"
      alt="Hosted by the OCF" style="border: 0;" />
      </a>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';

@Component
export default class Footer extends Vue {}
</script>

<style lang="scss">
.footer {
  background-color: $bluise;
}

.string1 {
  color: #FFFFFF;
 }
</style>
