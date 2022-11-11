<template>
  <div class="h-screen flex w-sreen block">
    <div class="flex w-screen">
      <div class="mx-auto">
        <nuxt-img class="mx-auto w-50 px-12 py-12" src="/assets/logo.webp" />
        <div
          class="bg-clip-padding backdrop-filter backdrop-blur-xl bg-opacity-50 bg-black mx-12 rounded-lg drop-shadow-md"
        >
          <h4
            class="py-4 md:mx-54 mb-8 mx-8 font-extrabold text-transparent text-3xl bg-clip-text bg-gradient-to-r from-red-500 to-yellow-600 text-center drop-shadow-md"
          >
            Somos un proyecto colectivo que pretende cambiar el estigma social
            relacionado con el cannabis.
          </h4>
        </div>
        <div class="flex mb-10">
          <div
            class="inline-grid grid-cols-3 gap-6 w-full justify-content items-center"
          >
            <span class="w-12 mx-auto">
              <a href="https://www.facebook.com/Frecuencia-420-107148185351025">
                <nuxt-img class="drop-shadow-md" src="/assets/facebook.svg" />
              </a>
            </span>
            <span class="w-12 mx-auto">
              <a
                href="https://www.youtube.com/channel/UCGvPTttw1IevOa4ivAfPEUQ"
              >
                <nuxt-img class="drop-shadow-md" src="/assets/youtube.svg" />
              </a>
            </span>

            <span class="w-12 mx-auto">
              <a href="https://www.twitch.tv/frecuencia420">
                <nuxt-img class="drop-shadow-md" src="/assets/twitch.svg" />
              </a>
            </span>

            <span class="w-12 mx-auto">
              <a href="https://www.tiktok.com/@frecuencia420">
                <nuxt-img class="drop-shadow-md" src="/assets/tiktok.svg" />
              </a>
            </span>

            <span class="w-12 mx-auto">
              <a href="https://www.instagram.com/lafrecuencia420/">
                <nuxt-img class="drop-shadow-md" src="/assets/instagram.svg" />
              </a>
            </span>

            <span class="w-12 mx-auto">
              <a href="https://twitter.com/Frecuencia420">
                <nuxt-img class="drop-shadow-md" src="/assets/twitter.svg" />
              </a>
            </span>

            <span></span>

            <span class="w-12 mx-auto">
              <a href="https://soundcloud.com/frecuencia-420">
                <nuxt-img class="drop-shadow-md" src="/assets/soundcloud.svg" />
              </a>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
