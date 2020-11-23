<template>
  <div class="home">
    <img
      alt="Vue logo"
      src="../assets/logo.png"
      data="steve"
      power="strong"
      nameNAme="steve"
    />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  props: [],
});

function a(_data: any) {
  const v = {
    a: { data: 'a', c: 'b' },
    b: 'lov',
  };

  const c = [
    'data',
    'love',
    'inconst',
    'data',
    'data',
    'love',
    'inconst',
    'data',
    'data',
  ];

  return 'helloworld';
}
</script>
