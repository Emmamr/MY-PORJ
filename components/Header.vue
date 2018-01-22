<template>
  <el-menu class="header-root" mode="horizontal">
      <h1 class="header-title">foo</h1>
  
  <div class="nav-items">
      <el-menu-item index="1" class="nav-items">Home</el-menu-item>
      <el-submenu index="2">
    <template slot="title">Cities</template>
    <el-menu-item index="2-1">Religh</el-menu-item>
    <el-menu-item index="2-2">Wilgmington</el-menu-item>
    <el-menu-item index="2-3">Charlotte</el-menu-item>
  </el-submenu>
      <el-menu-item index="3">Contact</el-menu-item>
  </div>
  </el-menu>
</template>

<style>
.header-root{
    display: flex;
    width: 100%;
    align-items: center;
    background: ;
    font-size: .9em;
};

.header-title {
    margin-right: 0 15px;
     
}

.nav-items:hover{
color:#444;
}

.nav-items{
    margin-left: auto;
    display: flex;
    outline: none !important;
}
</style>

