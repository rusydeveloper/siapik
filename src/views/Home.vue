<template>
<div class="home">
  <v-parallax src="../assets/background-main.png" height="900">
    <v-row align="center" justify="center">
      <v-col class="text-center" cols="12">
        <v-card outlined>
          <v-list-item three-line>
            <v-list-item-content>
              <v-img
          :src="require('../assets/logo-kota-bandung.png')"
          class="my-3"
          contain
          height="120"
        />
              <div>
                DINAS KOPERASI DAN UMKM KOTA BANDUNG
              </div>
              <v-list-item-title>
                SIAPIK
              </v-list-item-title>
              <v-list-item-subtitle>SISTEM APLIKASI INFORMASI KOPERASI</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-card>
      </v-col>
    </v-row>
    <v-row>
      <v-col>
        <v-btn x-large to="/coopProfile">
          <v-icon left>
            mdi-pencil
          </v-icon>
          Profile Koperasi
        </v-btn>
      </v-col>
      <v-col>
        <v-btn x-large to="/coopTransformation">
          <v-icon left>
            mdi-pencil
          </v-icon>
          Transformasi
          Koperasi Modern
        </v-btn>
      </v-col>
      <v-col>
        <v-btn x-large  to="/coopCommerce">
          <v-icon left>
            mdi-pencil
          </v-icon>
          Belanja Online
          Koperasi
        </v-btn>
      </v-col>
      <v-col>
        <v-btn x-large to="/coopElearning">
          <v-icon left>
            mdi-pencil
          </v-icon>
          E-Learning
        </v-btn>
      </v-col>
    </v-row>

    <v-row>
      <v-col>
        <v-btn x-large  to="/coopGraphic">
          <v-icon left>
            mdi-pencil
          </v-icon>
          Grafik Koperasi
        </v-btn>
      </v-col>
      <v-col>
        <v-btn x-large to="/coopIssue">
          <v-icon left>
            mdi-pencil
          </v-icon>
          Pengaduan dan
          Pembinaan Koperasi
        </v-btn>
      </v-col>
      <v-col>
        <v-btn x-large  to="/coopCalendar">
          <v-icon left>
            mdi-pencil
          </v-icon>
          Kalendar
          Program Dinas
        </v-btn>
      </v-col>

    </v-row>

  </v-parallax>

</div>
</template>


