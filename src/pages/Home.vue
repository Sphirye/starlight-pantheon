<template>
   <v-parallax src="@/assets/hill_stars_lobby.webp" class="background-image">
      <v-container>
         <v-row justify="end">
            <v-col cols="5" class="d-flex flex-column align-center justify-center">
               
               <v-card color="rgba(81, 176, 211, 0.9)" width="100%">
                  <v-card-title class="text-center cr-text-bold stroke-text text-size-30 my-2">
                     Who is Starfruit Cookie?
                  </v-card-title>
                  
                  <v-card-text>
                     <a href="https://cookierun.fandom.com/wiki/Starfruit_Cookie" target="_blank">Starfruit Cookie</a> is the kindest 
                     and purest High Oracle that the Starlight Panteon has ever meet! She has been blessed with an lucid inmense talent to read
                     the messages from the stars.
                     
                     <br class="mb-4">
                     
                     She will always ensures that anyone who visits the temple receives a fair and warm prediction directly from the
                     sky constellations!
                  </v-card-text>
               </v-card>
               
               <br class="my-3">
               
               <v-card color="rgba(81, 176, 211, 0.9)">
                  <v-card-title class="text-center text-wrap cr-text-bold stroke-text text-size-30 my-2">
                     What is the Starlight Pantheon?
                  </v-card-title>
                  
                  <v-card-text>
                     The Starlight Pantheon is a sacred giant sanctuary where blessings flow like water only when being guided by the
                     right cookie. Its specially know by it strong bond with the stars constellations, which riches up the clarividence
                     range when it comes to read and receive messages from the stars.
                     
                     <br class="mb-4">
                     
                     If you stay enough, you will be able to stare stars moving in pairs during the sunset just like
                     they were dancing!
                     
                     <br class="mb-10">
                     
                     May Starfruit Cookie one day find anyone to dance with, too...?
                  </v-card-text>
               </v-card>
               
            </v-col>            
         </v-row>
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

.stroke-text {
   -webkit-text-stroke: 5px black;
   paint-order: stroke fill;
}
</style>