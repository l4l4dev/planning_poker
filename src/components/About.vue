<template>
  <div class="md-layout md-alignment-center">
    <div class="md-laytout-item">
      <h2>How to play</h2>
      <h3>Starting Game</h3>
      <ol>
        <li>Dealer makes a session for planning. then Dealer provide a session code.</li>
        <li>Member join to the session by the code.</li>
      </ol>
      <h3>In Game</h3>
      <ul>
        <li>Each member can decide own number.</li>
        <li>After all of members decided it, A result scre will be shown up.</li>
        <li>The result is sorted numbers with member's name.</li>
        <li>Dealer can reset the game.</li>
      </ul>
    </div>
  </div>
</template>


<script>
export default {
  name: "about",
  data() {
    return {};
  },
  created() {
    this.$store.dispatch('updateScreenTitle', "ABOUT")
  }
};
</script>

<style lang="scss" scoped>
</style>