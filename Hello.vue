<template>
  <div id="root">
    <div v-for="item in items" :key="item.id">{{ item }}</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        { name: "apple", color: "red" },
        { name: "bannan", color: "yellow" }
      ]
    };
  },
  methods: {
    name() {}
  },
  computed: {
    name() {
      return this.data;
    }
  }
};
</script>

<style lang="scss" scoped>
</style>