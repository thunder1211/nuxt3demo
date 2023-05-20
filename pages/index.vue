<template>
  <NuxtLink to="/">Home</NuxtLink>
  <NuxtLink to="/about">About</NuxtLink>
  <div>Contents of Home page</div>
  <div>22222</div>
  <img src="../assets/images/moreArticle-02.jpg" />
</template>

<style lang="scss" scoped>
.router-link-active{
  color: #d86f4b;
  position: relative;
  &::after{
    content: '';
    display: block;
    width: 100%;
    height: 2px;
    border-radius: 10px;
    background-color: #d86f4b;
    position: absolute;
    left: 0;
    bottom: -5px;
  }
}
</style>