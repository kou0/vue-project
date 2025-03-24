<script setup>
import { ref } from 'vue'

const msg = ref('Hello World!')
</script>

<template>
  <div>
    <button>メイン</button>
    <button class="ml-2">申請一覧</button>
  </div>
  <div>
    <button>年次休暇申請</button>
    <button class="ml-2">その他の休暇申請</button>
  </div>
</template>

<style lang="css" scoped>
.ml-2 {
  margin-left: 12px;
}
</style>