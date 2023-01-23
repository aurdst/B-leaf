<template>
  <v-app>
    <v-app-bar
      app
      color="rgba(255, 0, 0, 0);"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="./assets/logo_bl.png"
          transition="scale-transition"
          width="60"
        />

      </div>

      <v-spacer></v-spacer>

      <p>Menu here</p>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
