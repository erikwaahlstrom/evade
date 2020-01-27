<template>
  <div>
    <canvas ref="game" class="canvas"></canvas>
    <character></character>
  </div>
</template>

<script>
import Character from "./Character";
export default { components: { Character } };
</script>

<style>
.canvas {
  width: 640px;
  height: 480px;
  border: 1px solid black;
}
</style>