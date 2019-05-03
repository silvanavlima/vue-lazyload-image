<template>
  <img
    :data-src="lazySrc"
    :data-srcset="lazySrcset"
    :style="style"
    class="AppImage"
  />
</template>

<script>
import lozad from "lozad";

export default {
  name: "Image"
};
</script>

<style lang="scss">
// Responsive image styles.
.AppImage {
  max-width: 100%;
  max-height: 100%;
  width: auto;
  height: auto;
  vertical-align: middle;
}
</style>
