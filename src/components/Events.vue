<script setup>
import { ref } from 'vue';
    const events=ref([
        {
            name:"Community Outreach at Northern Kenya",
            image:"../../public/events/degleex-ganzorig-0kIbj3yEvOM-unsplash.jpg",
            date:"July 6th 2025",
            location:"Northern Kenya School",
            category:"Community Outreach"
        },
                {
            name:"Course Fair",
            image:"../../public/events/belgutei-Nek28k7Jksc-unsplash.jpg",
            date:"July 28th 2025",
            location:"Kabete",
            category:"Course Fair"
        },

                {
            name:"Cultural Celebrations",
            image:"../../public/events/ibrahima-toure-QGu6C_pP28g-unsplash.jpg",
            date:" September 5th 2025",
            location:"Jutegemee Universty",
            category:"Cultural celebrations"
        },

                {
            name:"Sport Activities",
            image:"../../public/events/rosario-fernandes-XZBgm9ZWjq4-unsplash.jpg",
            date:"September 23rd 2025 ",
            location:"Mpisha",
            category:"Sport Acivities"
        }

    ])

</script>


<template>
    <v-container>
        <v-row>
            <v-col md="4" v-for="event in events" :key="event">
                 <v-card
    class="mx-auto"
    max-width="400"
  >
    <v-img
      class="align-end text-white"
      height="200"
      :src="event.image"
      cover
    >
      <v-card-title>{{event.name}}</v-card-title>
    </v-img>

    <v-card-subtitle class="pt-4">
      {{event.date }}
    </v-card-subtitle>

    <v-card-text>
      <div>{{ event.location }} </div>

       </v-card-text>

    <v-card-actions>
      <v-btn color="orange" :text="event.category"></v-btn>

      <v-btn color="orange" text="Explore"></v-btn>
    </v-card-actions>
  </v-card>

            </v-col>
        </v-row>

    </v-container>
</template>