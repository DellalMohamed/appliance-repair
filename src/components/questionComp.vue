<template>
  <section class="asked_questions">
    <v-card class="questions_intro mx-auto" elevation="0">
      <h1 class="questions_intro_title">Frequently asked questions</h1>
      <p class="questions_intro_text">
        We've compiled FAQs for your convenience. If your question isn't listed
        contact us via phone or email for a knowledgeable response.
      </p>
    </v-card>
    <v-card>
      <v-expansion-panels class="ex_panls" variant="accordion">
        <v-expansion-panel
          class="mb-2"
          text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
          title="How much will it cost to repair my appliance ?"
        ></v-expansion-panel>
        <v-expansion-panel
          class="mb-2"
          text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
          title="What’s better, a appliance repair or replacement?"
        ></v-expansion-panel>
        <v-expansion-panel
          class="mb-2"
          text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
          title="Can the manufacturer fix my appliance?"
        ></v-expansion-panel>
        <v-expansion-panel
          class="mb-2"
          text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
          title="My appliance won’t turn on, what should i do?"
        ></v-expansion-panel>
        <v-expansion-panel
          class="mb-2"
          text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
          title="Do you have a warranty services"
        ></v-expansion-panel>
      </v-expansion-panels>
    </v-card>
  </section>
</template>
<style lang="scss" scoped>
.asked_questions {
  width: 1028px;
  margin-left: 204px;
  .questions_intro {
    width: 816px;
    margin-bottom: 60px;
  }
  .ex_panls {
    width: 1028px;
    margin-bottom: 106px;
    .expansion_panel {
      height: 60px;
      margin-bottom: 10px;
      background-color: #42b983;
    }
  }
}
</style>
