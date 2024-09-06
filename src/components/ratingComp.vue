<template>
  <section class="rating w-100">
    <v-row class="d-flex justify-space-between">
      <v-col cols="12" class="card_col d-flex justify-center">
        <v-card class="ma-0" elevation="0">
          <div><img src="@/assets/Frame 95.svg" alt="" /></div>
          <v-card-title class="rating_title">Google</v-card-title>
          <h3>4.9</h3>
          <v-rating
            class="rating_el d-flex justify-space-between ga-12"
            color="warning"
            length="5"
            size="30"
            elevation="0"
          ></v-rating>
          <span>196 reviews</span>
        </v-card>
        <v-card class="ma-0" elevation="0">
          <div><img src="@/assets/star.svg" alt="" /></div>
          <v-card-title>Trustpilot</v-card-title>
          <h3>4.9</h3>
          <v-rating
            class="rating_el d-flex justify-space-between"
            color="warning"
            length="5"
            size="30"
            elevation="0"
          ></v-rating>
          <span>196 reviews</span>
        </v-card>
        <v-card class="ma-0" elevation="0">
          <div>
            <img src="@/assets/pngfind 1.svg" alt="" />
          </div>
          <v-card-title>HomeStars</v-card-title>
          <h3>98%</h3>
          <v-rating
            class="rating_el d-flex justify-space-between"
            color="warning"
            length="5"
            elevation="0"
            size="30"
          ></v-rating>
          <span>196 reviews</span>
        </v-card>
      </v-col>
    </v-row>
  </section>
</template>
<style lang="scss" scoped>
.rating {
  width: 100%;
  margin: 100px 0 150px;
  .card_col {
    width: 182px;
    gap: 100px;
    img {
      margin-bottom: 24px;
    }
    .rating_title {
      font-family: "Inter";
      font-size: 24px;
      font-weight: 800 bold;
    }
    h3 {
      font-family: "Inter";
      font-size: 48px;
      font-weight: 800 bold;
      margin-bottom: 11px;
    }
    .rating_el {
      display: flex;
      justify-content: space-between;
      gap: 4px;
    }
  }
}
</style>
