<template>
  <div class="push"></div>
  <div class="footer center">
    <div>
      🌸🪷🌷🌼🌻
    </div>
    <div>
      <a href="https://samrajya.dev" target="_blank">SAMRAJYA</a> 🍏 {{ year }}
    </div>
    <div>
      🔗 <a href="https://linkedin.com/in/samrajya" target="_blank">LinkedIn</a> | <a href="https://github.com/samrajya-dev " target="_blank"></a>
    </div>
  </div>
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
