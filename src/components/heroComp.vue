<template>
  <section class="hero">
    <v-card class="hero_card text-start border-md ml-auto">
      <h1 class="hero_card_title">Appliance repair service near me</h1>
      <p>
        We repair a wide range of home appliances and make sure they work
        smoothly after installation, maintenance, and repair. All our
        specialists are well-trained and have certificates to offer home
        appliance repair services
      </p>
      <v-btn class="bg-error">Make Appointment</v-btn>
    </v-card>
  </section>
</template>
<style lang="scss" scoped>
.hero {
  width: 1443px;
  height: 690px;
  padding: 96px 102px;
  background-image: url("@/assets/home-appliance-repair.svg");
  .hero_card {
    width: 529px;
    padding: 60px;
    border-radius: 30px;
    .hero_card_title {
      font-family: "Inter";
      font-weight: 700 bold;
      font-size: 48px;
      margin-bottom: 20px;
      color: #000000;
    }
    p {
      font-family: "Inter";
      font-weight: 700;
      font-size: 18px;
      line-height: 32px;
      margin-bottom: 30px;
    }
  }
}
</style>
