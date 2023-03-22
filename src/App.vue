<template>
  <div id="app">
    <a-button type="primary">测试</a-button>
    <nav>
      <router-link to="/dashboard/analysis">Home</router-link> |
      <router-link to="/user">About</router-link>
    </nav>
    <div class="main">
      <router-view /> 
    </div>
  </div>
</template>

<style lang="less"></style>
