<template>
  <section class="about mx-auto">
    <h1>About Us</h1>
    <p class="prg">
      We offer diverse household commercial services: appliance repair,
      servicing, installation for any model<br />. Our 24/7 call center ensures
      help in emergencies. Schedule now for swift doorstep assistance!
    </p>
    <v-row>
      <v-col class="d-flex">
        <v-card class="about_card mr-8" elevation="0">
          <v-img></v-img>
          <v-card-title class="ab_card_title">Transparancy</v-card-title>
          <v-card-text class="ab_card_text"
            >We are 100% transparent. No more extra bills for “additional
            services”. With us, you will always know exactly how much the
            restoration will cost.</v-card-text
          >
        </v-card>
        <v-card class="about_card" elevation="0">
          <v-img></v-img>
          <v-card-title class="ab_card_title">Transparancy</v-card-title>
          <v-card-text class="ab_card_text"
            >We are 100% transparent. No more extra bills for “additional
            services”. With us, you will always know exactly how much the
            restoration will cost.</v-card-text
          >
        </v-card>
        <v-card class="about_card ml-8" elevation="0">
          <v-img></v-img>
          <v-card-title class="ab_card_title">Transparancy</v-card-title>
          <v-card-text class="ab_card_text"
            >We are 100% transparent. No more extra bills for “additional
            services”. With us, you will always know exactly how much the
            restoration will cost.</v-card-text
          >
        </v-card>
      </v-col>
    </v-row>
    <v-btn class="bg-error" text-blue>Make Appointment</v-btn>
  </section>
</template>
<style lang="scss" scoped>
.about {
  width: 1240px;
  margin-bottom: 150px;
  h1 {
    font-family: "Inter";
    font-weight: 700 bold;
    font-size: 40px;
    margin-bottom: 30px;
  }
  .prg {
    font-family: "Inter";
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    margin-bottom: 30px;
  }
  .about_card {
    width: 386px;
    margin-bottom: 30px;
    .ab_card_title {
      font-family: "Inter";
      font-weight: 600;
      font-size: 18px;
      margin-bottom: 20px;
      padding: 0;
    }
    .ab_card_title {
      font-family: "Inter";
      font-size: 18px;
    }
  }
}
</style>
