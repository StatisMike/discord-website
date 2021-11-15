<template>
  <div class="start-here">
    <h2>How to View All Channels After Joining</h2>
    <p class="guide-info">
      Welcome new members!
      <br /><br />
      After you have joined the server, please follow the instructions below to
      view all of the channels in the server.
      <br /><br />
      First, please read the server rules in their entirety.
      <br /><br />
      Please note, you won't be able to see the other channels in this server
      until you agree by clicking on the ✅ in the 🙅rules channel located in
      ❗IMPORTANT category.
      <br /><br />
      <img
        :src="rulesCheckmark"
        alt="Confirm rules green checkmark"
        class="guide-info-image"
      />
      <br />
      PLEASE NOTE - This channel is not where you post R questions. To ask a
      question, you must first follow the instructions above. Then to ask your
      question, you need to first read the instructions in 📜r-help-read-me
      channel then create a thread detailing your question with supporting code
      and data in the 🤔r-help channel. Both of these channels are located in
      the R PROGRAMMING HELP category.
    </p>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line @typescript-eslint/explicit-module-boundary-types
  data() {
    return {
      rulesCheckmark: require("/src/assets/confirm-rules-checkmark.png"),
    };
  },
};
</script>

<style scoped>
p {
  margin: 0 auto;
  max-width: 550px;
  padding: 12px;
  text-align: left;
}
</style>
