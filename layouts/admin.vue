<script lang="ts" setup></script>

<template>
  <div class="container h-screen w-full flex flex-row gap-x-4 pt-[80px] relative">
    <div class="w-[300px] flex flex-col gap-y-3 fixed top-[80px]">
      <NuxtLink to="/dashboard/videos" class="w-[200px] border border-pink-700 p-3">Videos</NuxtLink>
      <NuxtLink to="/dashboard/users" class="w-[200px] border border-pink-700 p-3">Users</NuxtLink>
      <NuxtLink to="/dashboard/home" class="w-[200px] border border-pink-700 p-3">Logout</NuxtLink>
    </div>

    <div class="w-full ml-[250px]">
      <slot />
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}

@media (min-width: 768px) {
  .container {
    width: 750px;
  }
}

@media (min-width: 992px) {
  .container {
    width: 970px;
  }
}

@media (min-width: 1200px) {
  .container {
    width: 1170px;
  }
}
</style>
