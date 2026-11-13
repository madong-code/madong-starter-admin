<script lang="ts" setup>
import { AuthenticationQrCodeLogin } from '#/core/ui/common';
import { LOGIN_PATH } from '#/core/shared/constants';

defineOptions({ name: 'QrCodeLogin' });
</script>

<template>
  <AuthenticationQrCodeLogin :login-path="LOGIN_PATH" />
</template>
