<template>
   <footer class=" container flex  md:flex-row gap-2 justify-between  flex-wrap">
      <div>
         <h1 class="md:text-3xl text-lg font-bold ">KRYPTO</h1>
         <p class=" font-semibold text-center pt-2">by ZUZ ❤️</p>
      </div>
      <div>
         <h3> KRYPTO</h3>
         
         <ul>
            <li><a href="">HOME</a></li>
            <li><a href="">ABOUT</a></li>
            <li><a href="">BUY NFTs</a></li>
            <li><a href="">SELL NFTs</a></li>
         </ul>
      </div>
      <div>
         <h3>MARKIT</h3>
         <ul>
            <li><a href="">BROWSE NFTs</a></li>
            <li><a href="">BUY NFTs</a></li>
            <li><a href="">SELL NFTs</a></li>
         </ul>
      </div>
      <div>
         <h3> contact </h3>
         <ul>
            <li><a href="">email </a></li>
            <li><a href="">linkedin </a></li>
            <li><a href="">instagram </a></li>
            <li><a href="">twitter</a></li>
         </ul>
      </div>
      <div class=" pt-16 md:pt-0">
         <h3> join our newsletter </h3>
         <button
            class="md:p-4 md:px-12 p-2 px-6 rounded-full border-4 border-[#000000]  bg-[#000000]  tracking-wider font-bold mt-6 ">
            SUBMIT </button>
      </div>

   </footer>
</template>

<script setup>

</script>

<style scoped>
h3 {
   font-size: 20px;
   padding-bottom: 25px;
   font-weight: 700;
   text-transform: uppercase;
}

li {
   padding: 5px 0;
   font-weight: 500;
   text-transform: uppercase;
}

@media (max-width: 768px) {
   h3 {

      font-size: 16px;
   }

   li {
      font-size: 12px;
   }
}
</style>
