<template>
  <u-card class="w-full max-w-lg">
    <template #header>
      Login
    </template>

    <u-form class="space-y-6">
      <u-form-group label="Email">
        <u-input placeholder="Email" />
      </u-form-group>

      <u-form-group label="Password">
        <u-input type="password" placeholder="Password" />
      </u-form-group>


      <u-button type="submit">Login</u-button>
    </u-form>
  </u-card>
</template>

<script lang="ts" setup>

</script>
