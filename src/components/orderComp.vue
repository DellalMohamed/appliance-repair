<template>
  <section class="order">
    <div class="gruanteed rounded-circle">
      <div class="gruanteed_cont">
        <img src="../assets/Group 34.svg" alt="" />
      </div>
    </div>
    <v-row>
      <v-col>
        <v-card class="pay mx-auto bg-transparent elevation-0">
          <v-card-title class="pay_title"
            >You pay only for the jobs done. And done well.</v-card-title
          >
          <v-card-text class="pay_text">
            Need same-day appliance repair? We're available 24/7 to answer your
            questions and address household<br />
            appliance issues. Our technicians start repairs promptly upon
            appointment.
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="job_pay d-flex justify-center">
        <v-card color="transparent" elevation="0">
          <div class="img_cont">
            <img src="@/assets/Vector11.svg" alt="" />
          </div>
          <v-card-text class="job_pay_title">
            Book Online Or With Phone
          </v-card-text>
          <v-card-text class="job_pay_text"
            >Lorem ipsum dolor sit amet,<br />
            consectetur adipiscing elit. In<br />
            semper pretium quam</v-card-text
          >
        </v-card>
        <v-divider
          class="divider1"
          color="white"
          length="164"
          :thickness="2"
        ></v-divider>
        <v-card color="transparent" elevation="0">
          <div class="img_cont">
            <img src="@/assets/Vector12.svg" alt="" />
          </div>
          <v-card-text class="job_pay_title">
            We Identify the Problem
          </v-card-text>
          <v-card-text class="job_pay_text"
            >Lorem ipsum dolor sit amet,<br />
            consectetur adipiscing elit. In<br />
            semper pretium quam</v-card-text
          >
        </v-card>
        <v-divider
          class="divider1"
          color="white"
          length="164"
          :thickness="2"
        ></v-divider>
        <v-card color="transparent" elevation="0">
          <div class="img_cont">
            <img src="@/assets/Vector13.svg" alt="" />
          </div>
          <v-card-text class="job_pay_title">
            Our Professionals Arives
          </v-card-text>
          <v-card-text class="job_pay_text"
            >Lorem ipsum dolor sit amet,<br />
            consectetur adipiscing elit. In<br />
            semper pretium quam</v-card-text
          >
        </v-card>
        <v-divider
          class="divider1"
          color="white"
          length="164"
          :thickness="2"
        ></v-divider>
        <v-card color="transparent" elevation="0">
          <div class="img_cont">
            <img src="@/assets/Vector14.svg" alt="" />
          </div>
          <v-card-text class="job_pay_title">
            We Solve Your Problem
          </v-card-text>
          <v-card-text class="job_pay_text"
            >Lorem ipsum dolor sit amet,<br />
            consectetur adipiscing elit. In<br />
            semper pretium quam</v-card-text
          >
        </v-card>
      </v-col>
    </v-row>
    <v-btn class="order_btn bg-error">Make Appointment</v-btn>
  </section>
</template>

<style lang="scss" scoped>
.order {
  width: 1499px;
  margin-bottom: 120px;
  position: relative;
  background-image: linear-gradient(to right, #1a2d72, #37445e);
  .gruanteed {
    width: 182px;
    height: 182px;
    position: absolute;
    top: -10%;
    left: 50%;
    transform: translateX(-50%);
    position: relative;
    margin-bottom: 20px;
    .gruanteed_cont {
      width: 162px;
      height: 162px;
      border-radius: 50%;
      position: absolute;
      top: 10px;
      left: 10px;
      display: flex;
      justify-content: center;
    }
  }
  .pay {
    width: 893px;
    .pay_title {
      font-family: "Inter";
      font-size: 40px;
      font-weight: 700 bold;
      margin-bottom: 30px;
      padding: 0;
      color: #fff;
    }
    .pay_text {
      font-family: "Inter";
      font-size: 18px;
      font-weight: 400;
    }
  }
  .job_pay {
    .img_cont {
      max-width: 52px;
      min-height: 52px;
      padding: 13px 0;
      background-color: #c70039;
      margin: 0 auto 20px;
      border-radius: 10px;
      display: flex;
      justify-content: center;
    }
    .job_pay_title {
      font-family: "Inter";
      font-size: 18px;
      font-weight: 600;
      margin-bottom: 15px;
      padding: 0;
    }
    .job_pay_text {
      font-family: "Inter";
      font-size: 16px;
      font-weight: 400;
      padding: 0;
    }
    .divider1 {
      margin: 25px -67px;
      z-index: 2;
    }
  }
  .order_btn {
    margin: 90px 0 105px;
  }
}
</style>
