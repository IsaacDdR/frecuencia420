<!-- Please remove this file from your project -->
<template>
  <div id="vanta-selector">
    <MainContent />
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
