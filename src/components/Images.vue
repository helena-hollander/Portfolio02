<!--I dette Vue doc, har jeg skabt mit Images komponent, med en smule GSAP animation og diverse attributes-->

<script>
//Har impoteret min GSAP, efter jeg installerede den i terminalen
import { gsap } from "gsap"
export default {
        methods: {
        clickHandler(event) {
        gsap.to(event.target, {
            y:-50,
            ease: "expo",
            delay: 0.1,
            duration: 2,
        })
        },
    },
    


    props: {
        image: String,
    }
}
</script>




<template>
<!--Min div lytter '@' på hvornår musen hover over min div-->
    <div @mouseenter="clickHandler" class="p-4  m-0">         
        <h1>{{title}}</h1>         
        <img v-bind:src="image" alt="" class="aspect-3/4 object-cover h-full ">            
     </div>


</template>
