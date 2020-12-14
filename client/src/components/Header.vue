<template>
  <section class="section">
    <div class="container">
      <h1 class="title">{{ title }}</h1>
      <h2 class="subtitle">
        {{ subTitle }}
      </h2>
      <b-tooltip label="view code on GitHub" position="is-right">
        <a href="https://github.com/Pranjalya">
          <!-- <img src="../assets/GitHub_Logo.png" width="100" alt="GitHub Logo" /> -->
        </a>
      </b-tooltip>
    </div>
  </section>
</template>

<script>
export default {
  name: "Header",
  props: {
    title: {
      type: String,
      default: "Hacker Premiere League"
    },
    subTitle: {
      type: String,
      default: "Leaderboard and Match Simulation"
    }
  }
};
</script>

<style scoped></style>