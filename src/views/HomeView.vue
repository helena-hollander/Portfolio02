<script>
import Images from '../components/Images.vue'

export default {
    //Herunder lister jeg mine componeneter, så de kan kaldes i koden:
    components: {
    Images, 
  },
}
</script>


<template>
  <!--Ny section, med nyt grid-->
<section class="grid grid-cols-3 grid-flow-row absolute min-h-screen bg-rose-900 m-0 p-4">
   
  <!--Disse Images er hentet ind fra et komponenent, men med hver sin 'image attribute', så billedet kan variere mellem komponeneterne-->
          <Images image="src/assets/tulips-01.png"></Images>
          <Images image="src/assets/tulips_04.png"></Images>
          <Images image="src/assets/tulips_12.png"></Images>
          <Images image="src/assets/tulips_10.png"></Images>
          <Images image="src/assets/tulips_03.png"></Images>
          <Images image="src/assets/tulips_02.png"></Images>
  
  <h2 class="font-displayFont text-white text-xl">FONT?</h2>
  
  </section>
</template>
