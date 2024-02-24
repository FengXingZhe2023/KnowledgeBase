<script setup>
import HelloWorld from '@/components/HelloWorld.vue';

const handleClickMini = () => {
  AMessage.info('hello isboyjc, click mini AButton!')
};
</script>
<template>
  <div>hello isboyjc, This is toolsdog home page!</div>
  <a-space>
    <a-button type="primary" size="mini" @click="handleClickMini">Mini</a-button>
    <a-button type="primary" size="small">Small</a-button>
    <a-button type="primary">Medium</a-button>
    <a-button type="primary" size="large">Large</a-button>
  </a-space>
  <HelloWorld/>
  <!-- Icon -->
  <div>
    <icon-ep-alarm-clock class="" />
    <icon-home-down />
    <icon-user-right /> 
  </div>
  <button class="bg-blue-400 hover:bg-blue-500 text-sm text-white font-mono font-light py-2 px-4 rounded border-2 border-blue-200 dark:bg-blue-500 dark:hover:bg-blue-600">
  Button
</button>
</template>
<style scoped lang="scss">
</style>
