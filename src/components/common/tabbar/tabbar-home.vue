<template>
  <div id="tab-bar">
  <slot></slot>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  #tab-bar {
    display: flex;
    justify-content: space-around;
    background-color: #f6f6f6;
    position: fixed;
    height: 49px;
    left: 0;
    right: 0;
    bottom: 0;
    box-shadow: 0 -1px 1px rgba(0, 0, 0, .1);
  }
</style>