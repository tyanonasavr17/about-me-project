<template>
  <h3>Классная фишка из CSS</h3>
  <video controls>
    <source :src="require('../assets/cssvideo.mp4')" type="video/mp4">
    Ваш браузер не поддерживает воспроизведение видео.
  </video>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>

video {
  width: 1000px;
  height: 500px;
}
</style>