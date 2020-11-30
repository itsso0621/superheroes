<script>
export default {
  name: "add-hero-btn",
  props: {
    text: String,
  },
};
</script>

<template>
  <a
    class="f6 grow no-underline br-pill ba ph3 pv2 mb2 dib mid-gray"
    href="#0"
    @click="$emit('add-hero', true)"
    >{{ text }}</a
  >
</template>
