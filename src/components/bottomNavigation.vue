<template>
  <v-bottom-navigation class="px-16 d-flex align-center bg-error" elevation="0">
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
</template>
