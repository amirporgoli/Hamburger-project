<template>
    <v-footer color="#1f1f1f" class="d-flex flex-column">
      <div class="px-4 py-2 bgtop w-100">
        <v-toolbar color="transparent" height="40">
          <span class="mr-2">Refund Policy</span>
          <v-spacer></v-spacer>
          <v-icon>mdi-cash-multiple</v-icon>
          <v-icon>mdi-currency-usd</v-icon>
          <v-icon>mdi-cash-100</v-icon>
        </v-toolbar>
      </div>
      <div class="d-flex w-100 bgmidum px-4 pb-10">
        <v-row>
          <v-col cols="12" sm="3">
            <h4 class="mt-2">Connect With us</h4>
            <span class="text-caption">Facebook</span><br />
            <span class="text-caption">Twitter</span><br />
            <span class="text-caption">Instagram</span><br />
            <span class="text-caption">Whatsapp</span><br />
            <span class="text-caption">Youtube</span><br />
            <span class="text-caption">Pinterest</span>
          </v-col>
          <v-col cols="12" sm="3">
            <h4 class="mt-2">More About Store</h4>
            <span class="text-caption">Multiple Branches</span><br />
            <span class="text-caption">Take Franchise</span><br />
            <span class="text-caption">Scheduled Offers</span><br />
            <span class="text-caption">Visit Kitchen</span><br />
            <span class="text-caption">Meet Our Team</span><br />
            <span class="text-caption">More Links</span>
          </v-col>
          <v-col cols="12" sm="3">
            <h4 class="mt-2">Offline Store</h4>
            <span class="text-caption">Address: Mazandaran/Nour</span><br />
            <span class="text-caption">Wheeling, West Virginia</span><br />
            <span class="text-caption">26003</span><br />
            <span class="text-caption">Contact: 09388125037</span><br />
            <span class="text-caption">304-650-2694</span><br />
            <span class="text-caption">Email: porgoliamir@gmail.com</span>
          </v-col>
          <v-col cols="12" sm="3">
            <h4 class="mt-2">Location</h4>
            <v-img src="/src/img/map.webp" height="150" class="ml-n16"></v-img>
          </v-col>
        </v-row>
      </div>
      <div class="px-4 py-2 bgtop text-center w-100">
        <v-icon class="mr-2">mdi-copyright</v-icon>
        {{ new Date().getFullYear() }} <strong>AmirHossin Porgoli</strong>
      </div>
    </v-footer>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style>
  .v-footer {
    padding: 0 !important;
  }
  .bgtop {
    background-color: #111111;
  }
  .bgmidum {
    background-color: #1f1f1f;
  }
  </style>
  