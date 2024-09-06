<template>
  <section class="testimonials mx-auto">
    <v-card class="testimonials-intro mx-auto" elevation="0">
      <h1 class="testimonials_title">Testimonials</h1>
      <p>
        Read reviews about our repair, installation and maintenance services<br />
        Our trained experts are always ready to help
      </p>
    </v-card>
    <v-row>
      <v-col class="testim_col">
        <div class="img_cont">
          <img src="../assets/Vector2.svg" alt="" />
        </div>
        <v-card class="testimonial_card text-start pa-8">
          <v-card-text class="testimonial_text"
            >Praesent vitae nisl eget eros pharetra gravida ut sit amet erat.
            Suspendisse ullamcorper lobortis fermentum. Duis in lacinia diam.
            Praesent est massa, interdum sit amet turpis sed, interdum tempus
            libero</v-card-text
          >
          <v-card-title class="testimonial_title"> Sarah Fisher </v-card-title>
          <v-card-subtitle class="testimonial_subtitle">
            Customer
          </v-card-subtitle>
        </v-card>
      </v-col>
      <v-col class="testim_col">
        <div class="img_cont">
          <img src="../assets/Vector2.svg" alt="" />
        </div>
        <v-card class="testimonial_card text-start pa-8">
          <v-card-text class="testimonial_text"
            >Praesent vitae nisl eget eros pharetra gravida ut sit amet erat.
            Suspendisse ullamcorper lobortis fermentum. Duis in lacinia diam.
            Praesent est massa, interdum sit amet turpis sed, interdum tempus
            libero</v-card-text
          >
          <v-card-title class="testimonial_title"> Sarah Fisher </v-card-title>
          <v-card-subtitle class="testimonial_subtitle">
            Customer
          </v-card-subtitle>
        </v-card>
      </v-col>
    </v-row>
  </section>
</template>
<style lang="scss" scoped>
.testimonials {
  width: 1029px;
  background-color: #fff;
  margin-bottom: 154px;
  .testimonials-intro {
    width: 816px;
    margin-bottom: 60px;
    .testimonials_title {
      font-family: "Inter";
      font-weight: 700 bold;
      font-size: 40px;
      margin-bottom: 30px;
    }
    p {
      font-family: "Inter";
      font-weight: 400;
      font-size: 18px;
    }
  }
  .testim_col {
    position: relative;
    .img_cont {
      position: absolute;
      top: 0;
      left: 30px;
      z-index: 2;
    }
    .testimonial_card {
      width: 499px;
      .testimonial_text {
        font-family: "Inter";
        font-weight: 400;
        font-size: 16px;
        line-height: 24px;
        margin-bottom: 59px;
      }
      .testimonial_title {
        padding: 0;
        font-family: "Inter";
        font-size: 18px;
        font-weight: 500;
        margin-bottom: 5px;
      }
      .testimonial_subtitle {
        font-family: "Inter";
        font-size: 16px;
        font-weight: 400;
        padding: 0;
      }
    }
  }
}
</style>
