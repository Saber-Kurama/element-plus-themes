<!--
 * @Author: saber
 * @Date: 2022-01-04 14:25:36
 * @LastEditTime: 2022-01-04 15:44:20
 * @LastEditors: saber
 * @Description: 
-->
<template>
  <div class="flex">
    <el-button type="primary" :icon="Edit"></el-button>
    <el-button type="primary" :icon="Share"></el-button>
    <el-button type="primary" :icon="Delete"></el-button>
    <el-button type="primary" :icon="Search">Search</el-button>
    <el-button type="primary">
      Upload<el-icon class="el-icon--right"><Upload /></el-icon>
    </el-button>
  </div>
</template>
<script setup lang="ts">
import { Edit, Share, Delete, Search, Upload } from '@element-plus/icons-vue'
</script>

<style>
/* :root {
  --el-color-primary: #409eff;
} */
</style>
