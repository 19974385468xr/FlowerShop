<template>
<div class="q-pa-md">
    <q-h3>员工</q-h3>
    <div class="q-gutter-md" style="max-width: 300px">
      <q-input v-model="text" label="姓名" />
    </div>
    <q-btn color="primary" label="Primary" />
</div>
</template>

<script lang='ts' setup>
import {ref} from 'vue';
const text = ref('');
</script>

<style>
</style>