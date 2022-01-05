<template>
  <a-layout id="components-layout-demo-top" class="layout">
    <a-layout-header>
      <div class="logo" />
      <nuxt-link to="/">首页</nuxt-link>
      <nuxt-link to="/about">关于</nuxt-link>
      <nuxt-link to="/login">登录</nuxt-link>

    </a-layout-header>
    <a-layout-content style="padding: 0 50px;  height:80vh">
      <nuxt/>
    </a-layout-content>
    <a-layout-footer style="text-align: center">
      Ant Design ©2018 Created by Ant UED
    </a-layout-footer>
  </a-layout>
</template>
<style>
#components-layout-demo-top .logo {
  width: 120px;
  height: 31px;
  background: rgba(255, 255, 255, 0.2);
  margin: 16px 24px 16px 0;
  float: left;
}
</style>
