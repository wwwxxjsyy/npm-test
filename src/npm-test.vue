<template>
  <div>
    <h2>{{ name }}</h2>
  </div>
</template>

<script>
export default {
  name: "hrsong_npmtest",
  components: {},
  props: {
    name: {
      type: String,
      default: "",
    },
  },
  data() {
    return {};
  },
  mounted() {},
  methods: {},
  destroyed() {},
};
</script>

<style scoped></style>
