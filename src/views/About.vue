<template>
  <a-alert banner type="success" message="About Vite" />
  <div class="m-5">
    <a-button type="primary" @click="router.go(-1)">Back</a-button>
  </div>
</template>

<script lang="ts" setup>
import { useRouter } from 'vue-router'

const router = useRouter()
</script>

<style lang="scss"></style>
