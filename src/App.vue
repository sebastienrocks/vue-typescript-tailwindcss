<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about" class="text-red">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="postcss">
  @import 'assets/styles/tailwind.postcss';
</style>
