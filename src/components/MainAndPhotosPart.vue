<template>
  <h1>Обо мне и не только</h1>
  <div class="container">
    <div class="frame">
      <div class="image-container">
        <img src="../assets/photo1.png">
        <div class="caption">Моё последнее селфи</div>
        <br>
      </div>
      <div class="image-container">
        <img src="../assets/photo2.png">
        <div class="caption">Фото из старшей школы (10 класс)</div>
      </div>
      <ProgStoryPart/>
      <LinkPart/>
      <VideoPart/>
    </div>
  </div>
</template>

<script>
import ProgStoryPart from "@/components/ProgStoryPart";
import LinkPart from "@/components/LinkPart";
import VideoPart from "@/components/VideoPart";

export default {
  components: {
    ProgStoryPart,
    LinkPart,
    VideoPart
  }
}
</script>

<style lang="css" scoped>

h1 {
  text-align: center;

}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin-top: 500px;
}

.frame {
  border: 1px solid #ccc;
  padding: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.image-container {
  text-align: center;
  margin-bottom: 10px;
}

.caption {
  margin-top: 5px;
}

img {
  width: auto;
  height: 500px;
}
</style>