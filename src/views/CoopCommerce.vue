<template>
<v-container fluid class="pa-0">
  <v-banner>
    <v-btn x-large to="/">
    <v-icon left>
      mdi-arrow-left
    </v-icon>
    KEMBALI
  </v-btn>
  </v-banner>
  
  <v-img :src="require('../assets/logo-kota-bandung.png')" class="my-3" contain height="120" />
  <div>
    DINAS KOPERASI DAN UMKM KOTA BANDUNG
    <br/>
    Belanja Bersama Koperasi
  </div>
   <v-btn x-large color="warning" href="https://belanja.nectico.com/" target="_blank" dark>
    Kunjungi Website untuk Selengkapnya
  </v-btn>
  <v-row align="center" justify="space-around">
    <v-img :src="require('../assets/CoopCalendarBackground.png')" class="my-3" contain />
  </v-row>
</v-container>
</template>
