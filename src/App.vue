<script setup>
import NavbarComponent from './components/NavbarComponent.vue';
import Features from './components/Features.vue';
import Footers from './components/Footers.vue';
import SidebarComponent from './components/SidebarComponent.vue';

</script>

<template>
  <div class="d-flex">
    <SidebarComponent/>
    <div class="flex-grow-1">
      <NavbarComponent/>
      <Features/>
      <Footers/>
    </div>
  </div>
</template>
