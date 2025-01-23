<script setup lang="ts">
import AIAgent from './components/AI-Agent.vue';
import CostumerServices from './components/CostumerServices.vue';
import UseMain from './components/UseMain.vue';
</script>

<template>
  <div class="mt-[106px]">
    <UseMain />
    <div class="min-[1900px]:mx-[18.4%] min-[1500px]:mx-[11%] mx-[5%] mb-[100px]">
      <CostumerServices />
    </div>
    <div class="">
      <AIAgent />
    </div>
  </div>
</template>
