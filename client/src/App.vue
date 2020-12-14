<template>
  <div id="app">
    <Header></Header>
    <Table></Table>
  </div>
</template>

<script>
import Table from "@/components/Table.vue";
import Header from "@/components/Header.vue";

export default {
  name: "app",
  components: {
    Table,
    Header
  }
};
</script>

<style lang="scss"></style>
