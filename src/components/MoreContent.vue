<template>
  <div></div>
  <input v-model="value"  class="more-content" placeholder="您可在此编写任意内容" type="text"/>
</template>

<style lang="scss" scoped>
.more-content {
  display: flex;
  align-items: center;
  justify-content: center;
  border: none;
  margin-top: 20px;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.2509803922);
  backdrop-filter: blur(10px);
  
}
input:focus{
    outline: none;
  }
</style>

<script setup>
import { ref } from 'vue';
const value = ref('')
</script>
