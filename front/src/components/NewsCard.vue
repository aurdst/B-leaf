<template>
    <div>
        <v-row align="center" justify="center">
            <v-col>
                <v-card
                  class="mx-auto"
                  max-width="344"
                >
                  <v-img
                    src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
                    height="200px"
                  ></v-img>
              
                  <v-card-title>
                    Top western road trips
                  </v-card-title>
              
                  <v-card-subtitle>
                    1,000 miles of wonder
                  </v-card-subtitle>
                </v-card>
            </v-col>
        </v-row>
    </div>


</template>

<script>
  export default {
    name:"NewsCard",

    data: () => ({
      show: false,
    }),
  }
</script>