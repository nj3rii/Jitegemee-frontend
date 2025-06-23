<script setup>

</script>

<template>
  <!--Rotating images-->
    <v-carousel>
  <v-carousel-item
    src="../../public/Images/andrey-zvyagintsev-Eyg5Z7ARjWk-unsplash.jpg"
    cover
  ></v-carousel-item>/v-carousel-item>

  <v-carousel-item
    src="../../public/Images/daniil-skatov-BZPKZ3hU2t8-unsplash.jpg"
    cover
  ></v-carousel-item>

  <v-carousel-item
    src="../../public/Images/sajan-rajbahak-ZClQ3QE9P4M-unsplash.jpg"
     cover
  ></v-carousel-item>
 <v-carousel-item
    src="../../public/Images/the-jopwell-collection-37w8CzPwwBI-unsplash.jpg"
    cover
  ></v-carousel-item>

</v-carousel>

<!--Latest from Jitegemee-->
<v-container>
  <v-row>
    <v-col cols="12" md="4">
      <v-card
        subtitle="Your Academic Journey"
        text="Explore our universtiy, programs,resources and campus llife"
        title="Welcome to university"
        color="blue"
      ></v-card>

      </v-col>

    <v-col cols="12" md="4">
      <v-card color="blue">
        <template v-slot:title>
          Activities
        </template>

        <template v-slot:subtitle>
        Sports
        </template>

        <template v-slot:text>
         We offer a diverse range of competitive and recreational sports, ensuring every student can find their passion, whether they're seasoned athletes or trying something new
        </template>
      </v-card>
</v-col>

    <v-col cols="12"md="4">
      <v-card color="blue">
       <v-card-item>
          <v-card-title>Modern design Aesthetics</v-card-title>

          <v-card-subtitle>Animations and Graphics</v-card-subtitle>
       </v-card-item>

        <v-card-text>
          Features like micro-animations, parallax scrolling, organic shapes, engaging gradients—and thoughtful white space—help create a polished, user-friendly design
          
        </v-card-text>
      </v-card>

      
    </v-col>
  </v-row>

</v-container>
<!-- Partners -->
 <v-container>
  <v-row>
        <v-col cols="12" md="2">
         <img src="../../public/Images/IBM_logo_in-400x280.jpg"></img>
         <img src="../../public/Images/Oracle-Logo-1995-Present-e1692419896204-400x280.png"></img>
         <img src="../../public/Images/deloitte-01-400x280.png"></img>
         <img src="../../public/Images/cio-e1692420410866.png"></img>
         <img src="../../public/Images/Intel-01-400x280.png"></img>
         <img src="../../public/Images/SAF-MAIN-LOGO-400x280.png"></img>
      
    </v-col>

  </v-row>
 </v-container>
</template>