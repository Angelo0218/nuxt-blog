<script setup lang="ts">
defineOgImage()
</script>

<template>
  <div class="py-5">
    <div class="sm:grid grid-cols-8 px-6 py-5 sm:py-9 gap-5 container max-w-5xl  mx-auto">
      <div class="col-span-5  max-w-md">
        <div class="flex justify-between">
          <div>
            <h1 class="text-xl sm:text-4xl  pb-2 font-bold ">
              Angelo 安傑洛
            </h1>

            <div class="my-3 space-x-3 pb-10">
              <NuxtLink
                to="https://github.com/Angelo0218" target="_blank"
                class="p-2 bg-gray-300 text-gray-800 rounded-md" aria-label="Github"
              >
                <Icon name="fa:github" size="1em" />
              </NuxtLink>
              <NuxtLink
                to="https://twitter.com/@Ajlo0218" target="_blank"
                class="p-2 bg-gray-300 text-gray-800 rounded-md" aria-label="Twitter"
              >
                <Icon name="fa:twitter-square" size="1em" />
              </NuxtLink>
            </div>
          </div>
          <div class="sm:hidden block col-span-3 pb-5">
            <NuxtImg src="/Angelo.png" width="125" height="115" quality="50" class="rounded-md" />
          </div>
        </div>
        <h3 class="text-base sm:text-3xl font-semibold pb-7 sm:pb-12">
          一位新手軟體工程師，熱愛網站開發。
        </h3>

        <p>
          嘿，我是Angelo。自從開始打造自己的網站以來，每天都在學習新東西。用VUE3、Node.js等工具做過幾個小項目，最喜歡的是一個線上養植物的網站。那個項目讓我在實戰中學會了不少。

          我對技術充滿好奇，喜歡邊做邊學。在我的網站上，你會看到我分享這段旅程的點點滴滴。希望你會喜歡。

          歡迎來到我的數位小天地！
        </p>
      </div>
      <div class="hidden sm:block col-span-3">
        <NuxtImg src="/Angelo.png" width="450" height="500" quality="50" class="rounded-md" />
      </div>
    </div>
  </div>
</template>
