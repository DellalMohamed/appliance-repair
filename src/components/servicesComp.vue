<template>
  <section class="services">
    <v-card class="text-center mx-auto elevation-0">
      <h1 class="text-black">Our Services</h1>
      <p class="text-black">
        Breakdowns of home appliances might make you abandon the course of your
        scheduled plans and cause a<br />tremendous mess in your kitchen or
        bathroom.Fortunately, you have reliable helpers!
      </p>
      <v-row>
        <v-col class="d-flex justify-center">
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img src="@/assets/VectorTrnsp.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Refrigerator<br />
              Repair</v-card-title
            >
          </v-card>
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img src="@/assets/Vector22.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Dishwasher<br />
              Repair</v-card-title
            >
          </v-card>
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img src="@/assets/Vector3.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Washer<br />Repair</v-card-title
            >
          </v-card>
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img src="@/assets/Vector4.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Dryer<br />
              Repair</v-card-title
            >
          </v-card>
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img class="mb-5" src="@/assets/Vector5.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Oven<br />
              Repair</v-card-title
            >
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col class="d-flex justify-center">
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img src="@/assets/Vector6.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Freezer<br />
              Repair</v-card-title
            >
          </v-card>
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img src="@/assets/Vector7.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Range Hood<br />
              Repair</v-card-title
            >
          </v-card>
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img class="mb-5" src="@/assets/Vector8.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Microwave<br />
              Repair</v-card-title
            >
          </v-card>
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img src="@/assets/Vector9.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Gas Appliance<br />
              Repair</v-card-title
            >
          </v-card>
          <v-card class="service_card mr-10 mb-8" elevation="0">
            <div class="service_img_cont">
              <img src="@/assets/Vector10.svg" alt="" />
            </div>
            <v-card-title class="service_title"
              >Stove<br />
              Repair</v-card-title
            >
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </section>
</template>
<style lang="scss" scoped>
.services {
  width: 1240px;
  margin: 152px auto 138px;
  h1 {
    font-weight: 700 bold;
    font-family: "Inter";
    font-size: 40px;
    margin-bottom: 30px;
    color: #fff;
  }
  p {
    font-family: "Inter";
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    margin-bottom: 30px;
    color: #fff;
  }
  .service_card {
    width: 156px;
    height: 159px;
    margin-right: 40px;
    background-image: url("@/assets/Vector.svg");
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    .service_img_cont {
      margin: 30px auto 10px;
    }
    .service_title {
      font-size: 16px;
      padding: 0;
      font-weight: 500;
      line-height: 20px;
      margin-bottom: 30px;
      color: #fff;
    }
  }
}
</style>
