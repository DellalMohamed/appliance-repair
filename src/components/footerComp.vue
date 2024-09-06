<template>
  <v-footer class="footer w-100 pa-0 d-flex flex-column">
    <v-card class="w-100" elevation="0">
      <figure>
        <iframe
          class="ma-0 w-100"
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d199666.5651251294!2d-121.58334177520186!3d38.56165006739519!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x809ac672b28397f9%3A0x921f6aaa74197fdb!2sSacramento%2C%20CA%2C%20USA!5e0!3m2!1sen!2sbd!4v1647608789441!5m2!1sen!2sbd"
          loading="lazy"
        ></iframe>
      </figure>
    </v-card>
    <!----contact us------->
    <section class="contact_us">
      <v-row class="w-100 ma-0 d-flex justify-center">
        <v-col class="pa-0 w-100">
          <v-card class="bg-transparent" elevation="0">
            <h2>Contact us</h2>
            <p>
              Our customer service representatives operate 24 hours including
              weekends holidays. If you<br />have any questions at all, feel
              free to give us a call at the number provided.
            </p>
          </v-card>
        </v-col>
      </v-row>
      <v-row class="contacts w-100 ma-0">
        <v-col class="d-flex justify-space-around mx-auto pa-0 w-100">
          <v-card class="contact bg-transparent" elevation="0">
            <div class="img_cont">
              <img src="@/assets/Vector_c1.svg" alt="" />
            </div>
            <v-card-title class="contact-title">Office</v-card-title>
            <v-card-text class="contact-text">
              68 Street North-west,<br />
              Halifax, ab, Canada
            </v-card-text>
          </v-card>
          <v-card class="contact bg-transparent" elevation="0">
            <div class="img_cont">
              <img src="@/assets/Vector_c2.svg" alt="" />
            </div>
            <v-card-title class="contact-title">Make a call</v-card-title>
            <v-card-text class="contact-text"> (866) 934-5887 </v-card-text>
          </v-card>
          <v-card class="contact bg-transparent" elevation="0">
            <div class="img_cont">
              <img src="@/assets/Vector_c3.svg" alt="" />
            </div>
            <v-card-title class="contact-title">Send me email</v-card-title>
            <v-card-text class="contact-text"> Send me email </v-card-text>
          </v-card>
        </v-col>
      </v-row>
      <v-row class="w-100 ma-0">
        <v-col class="pl-0 pb-5 pt-0">
          <v-text-field
            class="bg-white rounded-lg"
            hide-details="auto"
            label="Name"
          ></v-text-field>
        </v-col>
        <v-col class="pr-0 pb-5 pt-0">
          <v-text-field
            class="bg-white rounded-lg"
            hide-details="auto"
            label="Email Address"
          ></v-text-field>
        </v-col>
      </v-row>
      <v-row class="w-100 ma-0">
        <v-col class="pl-0 pb-5 pt-0">
          <v-text-field
            class="bg-white rounded-lg"
            hide-details="auto"
            label="Phone Number"
          ></v-text-field>
        </v-col>
        <v-col class="pr-0 pb-5 pt-0">
          <v-select
            class="bg-white rounded-lg"
            hide-details="auto"
            label="Select Services"
            :items="[
              'California',
              'Colorado',
              'Florida',
              'Georgia',
              'Texas',
              'Wyoming',
            ]"
          >
          </v-select>
        </v-col>
      </v-row>
      <v-row class="w-100 ma-0">
        <v-col cols="12" class="bg-redmx-auto pa-0">
          <v-textarea
            class="bg-white rounded-lg"
            hide-details="auto"
            label="Home Address"
          ></v-textarea>
        </v-col>
      </v-row>
      <v-btn class="d-flex justify-start my-16 bg-error">Send Message</v-btn>
    </section>
  </v-footer>
</template>
<style lang="scss" scoped>
.footer {
  background-color: #37445e !important;
  iframe {
    width: 100%;
    height: 367px;
    margin-bottom: 103px;
  }
  .contact_us {
    margin-top: 103px;
    h2 {
      font-family: "Inter";
      font-weight: 700 bold;
      font-size: 40px;
      margin-bottom: 30px;
      color: #fff;
    }
    p {
      font-family: "inter";
      font-weight: 400;
      font-size: 18px;
      line-height: 28px;
      margin-bottom: 71px;
      color: #fff;
    }
  }
  .contacts {
    .contact {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      align-items: center;
      .img_cont {
        width: 52px;
        height: 52px;
        padding: 10px;
        display: flex;
        justify-content: center;
        align-items: center;
      }
      .contact-title {
        font-family: "Inter";
        font-weight: 600;
        font-size: 18px;
        margin-bottom: 15px;
        padding: 0;
        color: #fff;
      }
      .contact-text {
        font-family: "Inter";
        font-weight: 400;
        font-size: 16px;
        color: #fff;
        padding: 0;
        margin-bottom: 62px;
      }
    }
  }
}
</style>
