<template>
  <div class="push"></div>
  <div class="footer center"> <a href="https://samrajya.dev" target="_blank">SAMRAJYA</a> 🍏 {{ year }}</div>
</template>
<script>
const d = new Date()
const currentYear = d.getFullYear()
export default {
  data() {
    return {
      year: currentYear
    }
  }
}
</script>
