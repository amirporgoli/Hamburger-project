<template>
  <v-system-bar color="#1f1f1f">
    <span>Welcome to Foodie</span>
    <v-spacer></v-spacer>
    <v-icon class="ms-2" icon="mdi mdi-facebook"></v-icon>
    <v-icon class="ms-2" icon="mdi mdi-linkedin"></v-icon>
    <v-icon class="ms-2" icon="mdi mdi-pinterest"></v-icon>
    <v-icon class="ms-2" icon="mdi mdi-twitter"></v-icon>
    <v-icon class="ms-2" icon="mdi mdi-instagram"></v-icon>
    <v-icon class="ms-2" icon="mdi mdi-youtube"></v-icon>
  </v-system-bar>
  <v-app-bar color="#1f1f1f" height="100" flat>
    <v-app-bar-title>
        <h2>Foodie</h2>
    </v-app-bar-title>
    <v-spacer></v-spacer>
    <v-card
      color="#141415"
      flat
      outlined
      height="50"
      width="500"
      class="mt-6 pt-1"
    >
      <v-row>
        <v-col cols="12" sm="10">
          <v-text-field
            density="compact"
            placeholder="Search"
            variant=""
          ></v-text-field>
        </v-col>
        <v-col cols="12" sm="2">
          <v-icon
            color="orange"
            icon="mdi mdi-magnify"
            size="large"
            class="mt-2 ml-4"
          ></v-icon>
        </v-col>
      </v-row>
    </v-card>
    <v-spacer></v-spacer>
     <div>
        <span class="text-caption ml-4">My Favorite</span><br/>
            <v-btn append-icon="mdi mdi-heart-outline" class="account">
                Wishlist
                <template v-slot:append>
                    <v-icon></v-icon>
                </template>
            </v-btn>
     </div>
     <v-divider vertical inset class="mr-6"></v-divider>
     <div>
        <span class="text-caption ml-4">Login/Signup</span><br />
        <v-btn append-icon="mdi mdi-lock-open-outline" class="account">
            My Account
            <template v-slot:append>
                <v-icon></v-icon>
            </template>
        </v-btn>
     </div>
     <v-divider vertical inset class="mr-6"></v-divider>
     <v-icon class="mr-10" icon="mdi mdi-shopping-outline"></v-icon>
  </v-app-bar>
  <v-app-bar color="#191919" flat height="50">
    <v-btn variant="text" color="orange">Home</v-btn>
    <v-btn variant="text" class="orange">Shop</v-btn>
    <v-btn variant="text" class="orange">Drinks</v-btn>
    <v-btn variant="text" class="orange">Blog</v-btn>
    <v-btn variant="text" class="orange">Contact Us</v-btn>
    <v-btn variant="text" class="orange">Update to Pro</v-btn>
    <v-spacer></v-spacer>
    <v-btn icon="mdi mdi-phone" density="comfortable" class="phone mr-2"></v-btn>
    <div>
        <span class="text-caption">Call to</span><br />class
        <span class="text-caption text-gray mr-2">09388125037</span>
    </div>
  </v-app-bar>
</template>

<script>
export default {

}
</script>

<style>
.account {
    transition-duration: 0.4s;
}
.account:hover {
    color: orange;
}
.phone {
    background-color: orange !important;
}
</style>