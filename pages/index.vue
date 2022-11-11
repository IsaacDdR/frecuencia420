<!-- Please remove this file from your project -->
<template>
  <div class="h-screen" id="vanta-selector">
    <div class="flex w-screen">
      <div class="mx-auto py-32">
        <nuxt-img class="mx-auto w-50 px-12" src="/assets/logo.webp" />
        <h4
          class="md:mx-54 my-12 font-extrabold text-transparent text-3xl bg-clip-text bg-gradient-to-r from-green-500 to-yellow-500 text-center"
        >
          Somos un proyecto colectivo que pretende cambiar el estigma social
          relacionado con el cannabis.
        </h4>
        <div class="flex">
          <div
            class="inline-grid grid-cols-3 gap-6 w-full justify-content items-center"
          >
            <span class="w-12 mx-auto">
              <a href="https://www.facebook.com/Frecuencia-420-107148185351025">
                <nuxt-img src="/assets/facebook.svg" />
              </a>
            </span>
            <span class="w-12 mx-auto">
              <a
                href="https://www.youtube.com/channel/UCGvPTttw1IevOa4ivAfPEUQ"
              >
                <nuxt-img src="/assets/youtube.svg" />
              </a>
            </span>

            <span class="w-12 mx-auto">
              <a href="https://www.twitch.tv/frecuencia420">
                <nuxt-img src="/assets/twitch.svg" />
              </a>
            </span>

            <span class="w-12 mx-auto">
              <a href="https://www.facebook.com/Frecuencia-420-107148185351025">
                <nuxt-img src="/assets/tiktok.svg" />
              </a>
            </span>

            <span class="w-12 mx-auto">
              <a href="https://www.instagram.com/lafrecuencia420/">
                <nuxt-img src="/assets/instagram.svg" />
              </a>
            </span>

            <span class="w-12 mx-auto">
              <a href="https://twitter.com/Frecuencia420">
                <nuxt-img src="/assets/twitter.svg" />
              </a>
            </span>

            <span></span>

            <span class="w-12 mx-auto">
              <a href="https://soundcloud.com/frecuencia-420">
                <nuxt-img src="/assets/soundcloud.svg" />
              </a>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    VANTA.CELLS({
      el: "#vanta-selector",
      mouseControls: true,
      touchControls: true,
      gyroControls: false,
      scale: 1.0,
    });
  },
};
</script>
