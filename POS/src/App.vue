<template>
  <div>
    <router-view :key="translationVersion" />
    <Toast />
    <POSFooter />
  </div>
</template>

<script setup>
import Toast from "@/components/common/Toast.vue"
import POSFooter from "@/components/common/POSFooter.vue"
import { translationVersion } from "@/utils/translation"
</script>
