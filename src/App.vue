<template>
  <p>sample-code</p>
  <p>sample-code</p>
  <div style="width: 800px">
    <ZoomImg
      class="h-[30rem]"
      :src="red"
      :zoom-scale="5"
      zoom-type="drag"
      :step="1"
      :show-zoom-btns="false"
    />
  </div>
  <br />
  <div style="width: 800px">
    <Magnifier :src="red" zoom-type="move" :zoom-scale="3" />
  </div>
</template>

<script setup lang="ts">
import red from "./assets/images/red.jpg";
import "./assets/css/main.css";
import ZoomImg from "./components/ZoomImg.vue";
import Magnifier from "./components/Magnifier.vue";
</script>
