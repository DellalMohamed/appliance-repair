<template>
  <v-row class="intro">
    <v-col cols="12  pa-16">
      <v-card class="intro_card pa-15 rounded-xl text-start" elevation="2">
        <h1 class="rounded-xl mt">Same day Halifax appliance repair</h1>
        <v-actions>
          <v-checkbox
            class="hjk"
            label="Flexible Call-To-Meet Appointments"
          ></v-checkbox>
          <v-checkbox label="Best warranty on Parts and Labor"></v-checkbox>
          <v-checkbox label="Truck Stocked With Parts"></v-checkbox>
        </v-actions>
        <v-btn class="bg-error">Make Appointment</v-btn>
      </v-card>
    </v-col>
  </v-row>
</template>
<style lang="scss" scoped>
.intro {
  background-image: url("@/assets/imagePl.png");
  width: 100%;
  .intro_card {
    width: 529px;
  }
}
</style>
