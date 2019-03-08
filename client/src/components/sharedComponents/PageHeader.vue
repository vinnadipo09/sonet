<template>
  <v-toolbar fixed class="brown" dark>
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <v-toolbar-title>ViadTechnologies</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat outline color="green" class="my-menus">Viad Center</v-btn>
        <v-btn flat class="my-menus">Home</v-btn>
        <v-btn flat class="my-menus">web Services</v-btn>
        <v-btn flat class="my-menus">Mobile Services</v-btn>
        <v-btn flat class="my-menus">Engineering Services</v-btn>
        <v-btn flat class="my-menus">Consultancy</v-btn>
        <v-btn flat class="my-menus">Online Store</v-btn>
        <v-btn flat class="my-menus">Promotion and Offers</v-btn>
        <v-btn flat class="my-menus">About Us</v-btn>
        <v-btn flat class="my-menus">Register</v-btn>
        <v-btn flat class="my-menus">Log In</v-btn>
        <v-btn flat class="my-menus">Log Out</v-btn>

    </v-toolbar-items>
  </v-toolbar>
</template>
<script>
export default {
  name: 'PageHeader',
  data () {
    return {
    // information
    }
  }
}
</script>

<style scoped>
.my-menus{
    text-transform: none !important;
}
.my-menus:hover {
    text-decoration: underline;
}
</style>
