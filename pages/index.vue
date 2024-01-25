<template>
  <div class="text-center flex flex-col space-y-12" v-if="user">
    <h1 class="text-5xl text-white">Welcome!</h1>

    <p>Your email address is: {{ user.email }}</p>
  </div>
</template>

<script setup lang="ts">
const user = useSupabaseUser();
</script>
