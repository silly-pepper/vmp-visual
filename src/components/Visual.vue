<template>
  <div id="unity-container">
    <iframe src="/Build/Build.html" frameborder="0" style="width: 1200px; height: 600px;"></iframe>
  </div>
</template>

<script>
export default {
  name: 'UnityView'
}
</script>

<style scoped>
#unity-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 20px;
}
</style>
