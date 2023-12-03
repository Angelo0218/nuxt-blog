<template>
  <div>
    <p class="text-black dark:text-zinc-300   text-2xl py-1 font-semibold">
      Angelo
    </p>
    <p class="py-2 dark:text-zinc-300  ">
      嗨，我是Angelo，使用VUE3、VITE和NUXT3做過一些小項目，最愛線上植物養成網站，歡迎來我的數位小天地！
    </p>
    <div class="my-3 space-x-3 pb-3">
      <NuxtLink
        to="https://github.com/Angelo0218" target="_blank" class="p-2 bg-gray-300 text-gray-800 rounded-md"
        aria-label="Github"
      >
        <Icon name="fa:github" size="1em" />
      </NuxtLink>
      <NuxtLink
        to="https://twitter.com/@Ajlo0218" target="_blank" class="p-2 bg-gray-300 text-gray-800 rounded-md"
        aria-label="Twitter"
      >
        <Icon name="fa:twitter-square" size="1em" />
      </NuxtLink>
    </div>
  </div>
</template>
