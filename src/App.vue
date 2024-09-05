<template>
  <v-layout>
    <v-card class="mx-auto" color="grey-lighten-3" max-width="100%">
      <v-layout>
        <v-app-bar>
          <template v-slot:prepend>
            <v-app-bar-nav-icon></v-app-bar-nav-icon>
          </template>

          <v-app-bar-title>Appliance Repair</v-app-bar-title>

          <v-spacer></v-spacer>
          <nav class="d-flex justify-space-between ga-2">
            <router-link to="/">about</router-link>
            <router-link to="/Service">Service</router-link>
            <router-link to="/Order">How To Order</router-link>
            <router-link to="/Tesonials">Tesonials</router-link>
            <router-link to="/Faqs">Faqs</router-link>
            <router-link to="/Contact">Contact</router-link>
          </nav>
        </v-app-bar>

        <v-main>
          <v-container class="pa-0 bg-white" fluid>
            <v-row class="intro">
              <v-col cols="12  pa-16">
                <v-card
                  class="intro_card pa-15 rounded-xl text-start"
                  elevation="2"
                >
                  <h1 class="rounded-xl mt">
                    Same day Halifax appliance repair
                  </h1>
                  <v-actions>
                    <v-checkbox
                      class="hjk"
                      label="Flexible Call-To-Meet Appointments"
                    ></v-checkbox>
                    <v-checkbox
                      label="Best warranty on Parts and Labor"
                    ></v-checkbox>
                    <v-checkbox label="Truck Stocked With Parts"></v-checkbox>
                  </v-actions>
                  <v-btn class="bg-error">Make Appointment</v-btn>
                </v-card>
              </v-col>

              <!------rating section-------->
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
                        <img src="../src/assets/pngfind 1.svg" alt="" />
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
              <!---about section-->
              <section class="about mx-auto">
                <h1>About Us</h1>
                <p class="prg">
                  We offer diverse household commercial services: appliance
                  repair, servicing, installation for any model<br />. Our 24/7
                  call center ensures help in emergencies. Schedule now for
                  swift doorstep assistance!
                </p>
                <v-row>
                  <v-col class="d-flex">
                    <v-card class="about_card mr-8" elevation="0">
                      <v-img></v-img>
                      <v-card-title class="ab_card_title"
                        >Transparancy</v-card-title
                      >
                      <v-card-text class="ab_card_text"
                        >We are 100% transparent. No more extra bills for
                        “additional services”. With us, you will always know
                        exactly how much the restoration will cost.</v-card-text
                      >
                    </v-card>
                    <v-card class="about_card" elevation="0">
                      <v-img></v-img>
                      <v-card-title class="ab_card_title"
                        >Transparancy</v-card-title
                      >
                      <v-card-text class="ab_card_text"
                        >We are 100% transparent. No more extra bills for
                        “additional services”. With us, you will always know
                        exactly how much the restoration will cost.</v-card-text
                      >
                    </v-card>
                    <v-card class="about_card ml-8" elevation="0">
                      <v-img></v-img>
                      <v-card-title class="ab_card_title"
                        >Transparancy</v-card-title
                      >
                      <v-card-text class="ab_card_text"
                        >We are 100% transparent. No more extra bills for
                        “additional services”. With us, you will always know
                        exactly how much the restoration will cost.</v-card-text
                      >
                    </v-card>
                  </v-col>
                </v-row>
                <v-btn class="bg-error" text-blue>Make Appointment</v-btn>
              </section>
              <!----------hero section----------->
              <section class="hero">
                <v-card class="hero_card text-start border-md ml-auto">
                  <h1>Appliance repair service near me</h1>
                  <p>
                    We repair a wide range of home appliances and<br />
                    make sure they work smoothly after installation,<br />
                    maintenance, and repair. All our specialists are<br />
                    well-trained and have certificates to offer home<br />appliance
                    repair services
                  </p>
                  <v-btn class="bg-error">Make Appointment</v-btn>
                </v-card>
              </section>
              <!------our services--------->
              <section class="services">
                <v-card class="text-center mx-auto elevation-0">
                  <h1>Our Services</h1>
                  <p>
                    Breakdowns of home appliances might make you abandon the
                    course of your scheduled plans and cause a<br />tremendous
                    mess in your kitchen or bathroom.Fortunately, you have
                    reliable helpers!
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
                          >Refrigerator<br />
                          Repair</v-card-title
                        >
                      </v-card>
                      <v-card class="service_card mr-10 mb-8" elevation="0">
                        <div class="service_img_cont">
                          <img src="@/assets/Vector3.svg" alt="" />
                        </div>
                        <v-card-title class="service_title"
                          >Refrigerator<br />
                          Repair</v-card-title
                        >
                      </v-card>
                      <v-card class="service_card mr-10 mb-8" elevation="0">
                        <div class="service_img_cont">
                          <img src="@/assets/Vector4.svg" alt="" />
                        </div>
                        <v-card-title class="service_title"
                          >Refrigerator<br />
                          Repair</v-card-title
                        >
                      </v-card>
                      <v-card class="service_card mr-10 mb-8" elevation="0">
                        <div class="service_img_cont">
                          <img class="mb-5" src="@/assets/Vector5.svg" alt="" />
                        </div>
                        <v-card-title class="service_title"
                          >Refrigerator<br />
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
                          >Refrigerator<br />
                          Repair</v-card-title
                        >
                      </v-card>
                      <v-card class="service_card mr-10 mb-8" elevation="0">
                        <div class="service_img_cont">
                          <img src="@/assets/Vector7.svg" alt="" />
                        </div>
                        <v-card-title class="service_title"
                          >Refrigerator<br />
                          Repair</v-card-title
                        >
                      </v-card>
                      <v-card class="service_card mr-10 mb-8" elevation="0">
                        <div class="service_img_cont">
                          <img class="mb-5" src="@/assets/Vector8.svg" alt="" />
                        </div>
                        <v-card-title class="service_title"
                          >Refrigerator<br />
                          Repair</v-card-title
                        >
                      </v-card>
                      <v-card class="service_card mr-10 mb-8" elevation="0">
                        <div class="service_img_cont">
                          <img src="@/assets/Vector9.svg" alt="" />
                        </div>
                        <v-card-title class="service_title"
                          >Refrigerator<br />
                          Repair</v-card-title
                        >
                      </v-card>
                      <v-card class="service_card mr-10 mb-8" elevation="0">
                        <div class="service_img_cont">
                          <img src="@/assets/Vector10.svg" alt="" />
                        </div>
                        <v-card-title class="service_title"
                          >Refrigerator<br />
                          Repair</v-card-title
                        >
                      </v-card>
                    </v-col>
                  </v-row>
                </v-card>
              </section>
              <!----Order section----->
              <section class="order">
                <div class="gruanteed rounded-circle">
                  <div class="gruanteed_cont">
                    <img src="@/assets/Group 34.svg" alt="" />
                  </div>
                </div>
                <v-row>
                  <v-col>
                    <v-card class="pay mx-auto bg-transparent elevation-0">
                      <v-card-title class="pay_title"
                        >You pay only for the jobs done. And done
                        well.</v-card-title
                      >
                      <v-card-text class="pay_text">
                        Need same-day appliance repair? We're available 24/7 to
                        answer your questions and address household<br />
                        appliance issues. Our technicians start repairs promptly
                        upon appointment.
                      </v-card-text>
                    </v-card>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col class="job_pay d-flex justify-center">
                    <v-card color="transparent" elevation="0">
                      <div class="img_cont">
                        <img src="../src/assets/Vector11.svg" alt="" />
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
                        <img src="../src/assets/Vector12.svg" alt="" />
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
                        <img src="../src/assets/Vector13.svg" alt="" />
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
                        <img src="../src/assets/Vector14.svg" alt="" />
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
                  </v-col>
                </v-row>
                <v-btn class="order_btn bg-error">Make Appointment</v-btn>
              </section>
              <!--------- testimonial section  -->
              <section class="testimonials mx-auto">
                <v-card class="testimonials-intro mx-auto">
                  <h1 class="testimonials_title">Testimonials</h1>
                  <p>
                    Read reviews about our repair, installation and maintenance
                    services<br />
                    Our trained experts are always ready to help
                  </p>
                </v-card>
                <v-row>
                  <v-col class="testim_col">
                    <div class="img_cont">
                      <img src="../src/assets/Vector2.svg" alt="" />
                    </div>
                    <v-card class="testimonial_card text-start pa-8">
                      <v-card-text class="testimonial_text"
                        >Praesent vitae nisl eget eros pharetra gravida ut sit
                        amet erat. Suspendisse ullamcorper lobortis fermentum.
                        Duis in lacinia diam. Praesent est massa, interdum sit
                        amet turpis sed, interdum tempus libero</v-card-text
                      >
                      <v-card-title class="testimonial_title">
                        Sarah Fisher
                      </v-card-title>
                      <v-card-subtitle class="testimonial_subtitle">
                        Customer
                      </v-card-subtitle>
                    </v-card>
                  </v-col>
                  <v-col class="testim_col">
                    <div class="img_cont">
                      <img src="../src/assets/Vector2.svg" alt="" />
                    </div>
                    <v-card class="testimonial_card text-start pa-8">
                      <v-card-text class="testimonial_text"
                        >Praesent vitae nisl eget eros pharetra gravida ut sit
                        amet erat. Suspendisse ullamcorper lobortis fermentum.
                        Duis in lacinia diam. Praesent est massa, interdum sit
                        amet turpis sed, interdum tempus libero</v-card-text
                      >
                      <v-card-title class="testimonial_title">
                        Sarah Fisher
                      </v-card-title>
                      <v-card-subtitle class="testimonial_subtitle">
                        Customer
                      </v-card-subtitle>
                    </v-card>
                  </v-col>
                </v-row>
              </section>

              <!--------- question section ------>
              <section class="asked_questions">
                <v-card class="questions_intro mx-auto" elevation="0">
                  <h1 class="questions_intro_title">
                    Frequently asked questions
                  </h1>
                  <p class="questions_intro_text">
                    We've compiled FAQs for your convenience. If your question
                    isn't listed contact us via phone or email for a
                    knowledgeable response.
                  </p>
                </v-card>
                <v-card>
                  <v-expansion-panels class="ex_panls" variant="accordion">
                    <v-expansion-panel
                      text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
                      title="How much will it cost to repair my appliance ?"
                    ></v-expansion-panel>
                    <v-expansion-panel
                      text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
                      title="What’s better, a appliance repair or replacement?"
                    ></v-expansion-panel>
                    <v-expansion-panel
                      text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
                      title="Can the manufacturer fix my appliance?"
                    ></v-expansion-panel>
                    <v-expansion-panel
                      text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
                      title="My appliance won’t turn on, what should i do?"
                    ></v-expansion-panel>
                    <v-expansion-panel
                      text="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."
                      title="Do you have a warranty services"
                    ></v-expansion-panel>
                  </v-expansion-panels>
                </v-card>
              </section>
              <!-----------footer---------------->
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
                          Our customer service representatives operate 24 hours
                          including weekends holidays. If you<br />have any
                          questions at all, feel free to give us a call at the
                          number provided.
                        </p>
                      </v-card>
                    </v-col>
                  </v-row>
                  <v-row class="contacts w-100 ma-0">
                    <v-col
                      class="d-flex justify-space-around mx-auto pa-0 w-100"
                    >
                      <v-card class="contact bg-transparent" elevation="0">
                        <div class="img_cont">
                          <img src="../src/assets/Vector_c1.svg" alt="" />
                        </div>
                        <v-card-title class="contact-title"
                          >Office</v-card-title
                        >
                        <v-card-text class="contact-text">
                          68 Street North-west,<br />
                          Halifax, ab, Canada
                        </v-card-text>
                      </v-card>
                      <v-card class="contact bg-transparent" elevation="0">
                        <div class="img_cont">
                          <img src="../src/assets/Vector_c2.svg" alt="" />
                        </div>
                        <v-card-title class="contact-title"
                          >Make a call</v-card-title
                        >
                        <v-card-text class="contact-text">
                          (866) 934-5887
                        </v-card-text>
                      </v-card>
                      <v-card class="contact bg-transparent" elevation="0">
                        <div class="img_cont">
                          <img src="../src/assets/Vector_c3.svg" alt="" />
                        </div>
                        <v-card-title class="contact-title"
                          >Send me email</v-card-title
                        >
                        <v-card-text class="contact-text">
                          Send me email
                        </v-card-text>
                      </v-card>
                    </v-col>
                  </v-row>
                  <v-row class="w-100 ma-0">
                    <v-col class="pl-0">
                      <v-text-field
                        label="Solo"
                        placeholder="Placeholder"
                        variant="solo"
                      ></v-text-field>
                    </v-col>
                    <v-col class="pr-0">
                      <v-text-field
                        label="Solo"
                        placeholder="Placeholder"
                        variant="solo"
                      ></v-text-field>
                    </v-col>
                  </v-row>
                  <v-row class="w-100 pa-0 bg-white">
                    <v-col class="py-0 d-flex justify-start">
                      <v-text-field
                        label="Solo"
                        placeholder="Placeholder"
                        variant="solo"
                      ></v-text-field>
                    </v-col>
                    <v-col class="py-0">
                      <v-select
                        label="Select"
                        :items="[
                          'California',
                          'Colorado',
                          'Florida',
                          'Georgia',
                          'Texas',
                          'Wyoming',
                        ]"
                      ></v-select>
                    </v-col>
                  </v-row>
                  <v-row>
                    <v-textarea
                      class="bg-white w-100"
                      label="Label"
                    ></v-textarea>
                  </v-row>
                  <v-btn class="d-flex justify-start my-16 bg-error"
                    >Send Message</v-btn
                  >
                </section>
              </v-footer>
              <v-bottom-navigation
                class="px-16 d-flex align-center bg-error"
                elevation="0"
              >
                <div class="d-flex align-center">
                  <span>© 2023 Appliance repair</span>
                </div>
                <v-spacer></v-spacer>
                <div class="icon_bottom_cont d-flex justify-space-between ga-2">
                  <v-btn class="px-0" value="recent">
                    <v-icon>mdi-facebook</v-icon>
                  </v-btn>

                  <v-btn value="favorites">
                    <v-icon>mdi-twitter</v-icon>
                  </v-btn>
                  <v-btn value="nearby">
                    <v-icon>mdi-linkedin</v-icon>
                  </v-btn>
                  <v-btn value="nearby">
                    <v-icon>mdi-instagram</v-icon>
                  </v-btn>
                </div>
              </v-bottom-navigation>
            </v-row>
          </v-container>
        </v-main>
      </v-layout>
    </v-card>
  </v-layout>
  <router-view />
</template>

<style lang="scss">
//--------intro----------
.intro {
  background-image: url("@/assets/imagePl.png");
  width: 100%;
  .intro_card {
    width: 529px;
  }
}
//----rating--------------
.rating {
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
/////////   hero section /////
.hero {
  width: 1443px;
  padding: 96px 102px;
  background-image: url("../src/assets/home-appliance-repair.svg");
  .hero_card {
    width: 529px;
    padding: 60px;
    border-radius: 30px;
    h1 {
      font-family: "Inter";
      font-weight: 700 bold;
      font-size: 48px;
      margin-bottom: 20px;
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
// ------  services section -----
.services {
  width: 1240px;
  margin: auto;
  margin-bottom: 138px;
  h1 {
    font-weight: 700 bold;
    font-family: "Inter";
    font-size: 40px;
    margin-bottom: 30px;
  }
  p {
    font-family: "Inter";
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    margin-bottom: 30px;
  }
  .service_card {
    width: 156px;
    height: 159px;
    margin-right: 40px;
    background-image: url("../src/assets/Vector.svg");
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
    }
  }
}

//----order section ----
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
    margin: 159px 237px 60px 234px;
    .pay_title {
      font-family: "Inter";
      font-size: 40px;
      font-weight: 700 bold;
      margin-bottom: 30px;
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

///----------testimonial section--------------
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
      }
    }
  }
}
//---------questions section-------------
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
//---------------footer--------------------
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
.rating {
  width: 100%;
  margin: 100px 0 150px;
}
.mdi-checkbox-blank-outline {
  border-radius: 50px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  width: 604px;
  margin-right: 106px;
  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
