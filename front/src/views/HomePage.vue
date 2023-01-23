<template>
    <div>
        <!-- This part is only picture with the catch phrase -->
        <v-row>
            <v-col cols="6" class="mx-auto">
                <div class="ma-10">
                    <b>B'LEAF</b>
                    <br>  
                    <p>It's never too late to start heading in the<br>
                    right direction. -Seth Godin</p>
                    </div>
                    <v-btn class="ml-10">En savoir plus ! </v-btn>
            </v-col>

            <v-col cols="6" class="mx-auto">
                <v-img src="../assets/img_bleaf.png"></v-img>
            </v-col>
        </v-row>
        <!-- This part is for presentation of project -->
        <v-row>
            <v-col cols="6">
                <p class="text-center">text here </p>
            </v-col>
            <v-col cols="6">
                <v-img class="text-center">img here</v-img>
            </v-col>
        </v-row>

        <!-- This part is a first actuallity of Bleaf -->

        <v-row>
            <v-col cols="12"><h2 class="text-center">Title here</h2></v-col>
            <v-col cols="12">
                <CardInfo/>
            </v-col>
        </v-row>

        <!-- Here is a container for a video presentation -->

        <v-row>
            
        </v-row>

    </div>

</template>

<script>
  import CardInfo from '../components/CardInfo.vue'
  export default {
    name: 'HomePageBleaf',
    components: {CardInfo,}
  }
</script>
