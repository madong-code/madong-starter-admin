<script setup lang="ts">
import { IconifyIcon as VbenIcon } from '#/core/design/icons';

import { ElIcon } from 'element-plus';

const props = defineProps({
  icon: {
    type: String,
    default: '',
  },
});
</script>

<template>
  <ElIcon>
    <VbenIcon :icon="props.icon" />
  </ElIcon>
</template>
