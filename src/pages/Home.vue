<template>
    <v-parallax src="@/assets/hill_stars_lobby.webp" class="background-image">
        <v-container>
            <v-responsive>
                
                <v-row justify="end">
                    <v-col cols="5" class="d-flex flex-column align-center justify-center">
                    

                    <div class="text-center text-no-wrap cookie-run-font">
                        Who is Starfruit Cookie?
                    </div>
                    
                    <div>
                        <a href="https://cookierun.fandom.com/wiki/Starfruit_Cookie" target="_blank">Starfruit Cookie</a> is the kindest 
                        and purest High Oracle the Starlight Panteon has ever meet! She has been blessed with an lucid inmense talent to read
                        the messages from the stars.
                        
                        She will always ensures that anyone who visits the temple receives a fair and warm prediction directly from the
                        sky constellations!
                    </div>

                    <br class="my-8">

                    <div class="text-center text-no-wrap cookie-run-font">
                        What is the Starlight Pantheon?
                    </div>

                    <div>
                        The Starlight Pantheon is a sacred giant sanctuary where blessings flow like water only when being guided by the
                        right cookie. Its specially know by it strong bond with the stars constellations, which riches up the clarividence
                        range when it comes to read and receive messages from the stars.

                        <br class="mb-4">

                        If you stay enough, you will be able to stare stars moving in pairs during the sunset just like
                        they were dancing!

                        <br class="mb-16">
                        
                        May Starfruit Cookie find anyone to dance with, too...?
                    </div>


                    </v-col>
                    <v-divider thickness="10" color="success" class="border-opacity-100"></v-divider>

                </v-row>

            </v-responsive>
        </v-container>
    </v-parallax>
  </template>
  
  <script lang="ts" setup>
    //
  </script>

<style>
.background-image img {
    filter: blur(4px);
}
</style>