<template>
  <div class="view-box">
    <div id="toolbar">允许内部元素拖拽</div>
    <div class="container">
      <vue-drag-resize-rotate :enable-native-drag="false" :x="0" :y="0" :w="200" :h="200">
        <p>不允许浏览器原生JavaScript拖拽</p>
        <p>Native drag disabled. Try to drag the component from the ball.</p>
        <img :src="require('@/assets/ball.svg')" />
      </vue-drag-resize-rotate>
      <vue-drag-resize-rotate :enable-native-drag="true" :x="0" :y="200" :w="200" :h="200">
        <p>允许浏览器原生JavaScript拖拽</p>
        <p>Native drag enabled. Try to drag the component from the ball.</p>
        <img :src="require('@/assets/ball.svg')" />
      </vue-drag-resize-rotate>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
</style>