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
      minHeight: 800,
      scale: 1.0,
    });
  },
};
</script>
