<script setup lang="ts">
import zhCn from 'element-plus/lib/locale/lang/zh-cn';

const locale = zhCn;
</script>

<template>
  <div class="bg-black bg-opacity-85 h-full flex justify-center">
    <div>
      <Headbar></Headbar>
      <div class="flex justify-center">
        <div class="w-80px bg-black h-700px"></div>
        <div class="flex-auto">
          <router-view></router-view>
        </div>
      </div>
    </div>
    <div class="m-5">
      <!-- <el-config-provider :locale="locale"> -->
      <!-- </el-config-provider> -->
    </div>
  </div>
  <!-- <TheFooter></TheFooter> -->
</template>
