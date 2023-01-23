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

        <v-row style="background-color:#034256">
            <v-col cols="12"><h2 class="text-center">Title here</h2></v-col>
            <v-col cols="12">
                <CardInfo/>
            </v-col>
        </v-row>

        <!-- Here is a container for a video presentation -->

        <v-row>
            <v-col cols="12">
                <h2 class="text-center mt-15">B'LEAF <span style="color:green;">en action</span></h2>
            </v-col>

            <v-col cols="12" class="text-center mb-10 mt-10">
                <iframe width="550" height="300" src="https://www.youtube.com/embed/6uM2_13ZfYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </v-col>

            <v-col cols="12" class="text-center">
                <iframe width="150" height="110" class="mx-2" src="https://www.youtube.com/embed/6uM2_13ZfYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                <iframe width="150" height="110" class="mx-2" src="https://www.youtube.com/embed/6uM2_13ZfYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                <iframe width="150" height="110" class="mx-2" src="https://www.youtube.com/embed/6uM2_13ZfYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                <iframe width="150" height="110" class="mx-2" src="https://www.youtube.com/embed/6uM2_13ZfYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </v-col>
        </v-row>

        <!-- Here is the "Did you know ?" section -->

        <v-row style="background-color:#162A34">
            <v-col cols="6">
                <v-img class="text-center">Image Here</v-img>
            </v-col>
            <v-col cols="6">
                <p class="text-center">Text here</p>
            </v-col>
        </v-row>

        <!-- Here is the "Did you know ?" section -->

        <h2 class="text-center mt-16 mb-5" style="text-decoration: underline; text-decoration-color:green;">@B'leaf</h2>
        <v-row align="center" justify="center">
            <v-col cols="2">
                <NewsCard/>
            </v-col>

            <v-col cols="2">
                <NewsCard/>
            </v-col>

            <v-col cols="2">
                <NewsCard/>
            </v-col>
        </v-row>

        <v-row align="center" justify="center">
            <v-col cols="2">
                <NewsCard/>
            </v-col>

            <v-col cols="2">
                <NewsCard/>
            </v-col>

            <v-col cols="2">
                <NewsCard/>
            </v-col>
        </v-row>

        <v-row align="center" justify="center" class="mb-15 mt-6">
            <v-btn class="mr-5">Charger plus</v-btn>
            <v-btn>Suivre sur Instagram</v-btn>
        </v-row>

        <!-- Other section join_us -->

        <v-row>
            <div class="custom_bg_home_p">
                <v-col cols="9" class="mx-auto mt-15 mb-15 pa-15" style="background-color:rgba(3, 66, 86, 0.9);">
                    <h3 style="color:green">Rejoinez-nous</h3>
                    <h3 style="color:white">Aider à la défense, la préservation et la protection de notre planète !</h3>
                    <p style="color:white" class="mt-10">Ensemble, nous nous engageons à transmettre des valeurs fortes, telles que le respect et la valorisation de notre territoire. Nous avons conscience que, dans la société dans laquelle nous évoluons tous, l’environnement est devenu une thématique de plus en plus préoccupante.
                    </p>

                    <v-btn outlined color="white">Impliquez-vous</v-btn>
                </v-col>
            </div>
        </v-row>
    </div>

</template>

<script>
  import CardInfo from '../components/CardInfo.vue'
  import NewsCard from '../components/NewsCard.vue'
  export default {
    name: 'HomePageBleaf',
    components: {CardInfo,NewsCard}
  }
</script>
