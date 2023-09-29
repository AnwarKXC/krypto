<template>
<div class=" flex flex-col gap-20 pb-16">
   <NavBar/>
   <HeroSection/>
   <FeaturedSection/>
   <SecondSection/>
   <ThirdSection/>
   <CommentSection/>
   <LastSection/>
   <FooterSection/>
</div>
</template>

<script setup>
import FeaturedSection from './components/FeaturedSection.vue'
import HeroSection from './components/HeroSection.vue'
import NavBar from './components/NavBar.vue'
import SecondSection from './components/SecondSection.vue'
import ThirdSection from './components/thirdSection.vue'
import CommentSection from './components/CommentSection.vue'
import LastSection from './components/LastSection.vue'
import FooterSection from './components/FooterSection.vue'


</script>
