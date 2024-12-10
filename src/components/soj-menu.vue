<script setup>
import 'devui-theme/styles-var/devui-var.scss'
</script>

<template>
  <d-menu mode="horizontal" :default-select-keys="['home']" width="100%">
    <span id="title">Simple Online Judge</span>
    <d-menu-item key="home">
      <template #icon>
        <i class="icon-homepage"></i>
      </template>
      首页
    </d-menu-item>
    <d-menu-item key="problems">
      问题
    </d-menu-item>
    <d-menu-item key="contests">
      比赛
    </d-menu-item>
    <d-avatar gender="female" name="Dev"></d-avatar>
  </d-menu>
</template>

<style scoped lang="scss">
@import 'devui-theme/styles-var/devui-var.scss';
#title{
  float: left;
  font-size: $devui-font-size-page-title;
}
</style>