<template>
  <div class="flex flex-col dark:text-zinc-300    my-5 md:my-0 md:justify-self-center">
    <p class="text-black dark:text-zinc-300  text-base font-semibold">
      快速導覽
    </p>
    <NuxtLink to="/" class="hover:underline">
      首頁
    </NuxtLink>
    <NuxtLink to="/blogs" class="hover:underline">
      Blogs
    </NuxtLink>
    <NuxtLink to="/categories" class="hover:underline">
      分類
    </NuxtLink>
    <NuxtLink to="/about" class="hover:underline">
      關於我
    </NuxtLink>
  </div>
</template>
