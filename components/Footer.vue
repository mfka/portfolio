<template>
  <a-layout-footer :style="{ textAlign: 'center' }">
    Copyright ® All rights reserved {{ year }}. Created by Marek Firlejczyk
  </a-layout-footer>
</template>

<script lang="ts">
export default {
  setup() {
    const year = new Date().getFullYear()

    return { year }
  },
}
</script>
