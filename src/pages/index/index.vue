<script setup lang="ts">
import { ref } from 'vue'
const title = ref('Hello')
</script>

<template>
  <view class="content">
    <image class="logo" src="/static/logo.png" />
    <view class="text-area">
      <text class="title">
        {{ title }}
      </text>
    </view>
  </view>
</template>

<style lang="scss">
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.logo {
  height: rpx(150);
  width: rpx(150);
  margin: rpx(200) auto rpx(50);
}

.text-area {
  display: flex;
  justify-content: center;
}

.title {
  font-size: rpx(30);
  color: #8f8f94;
}
</style>
