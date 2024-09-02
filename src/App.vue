<script setup>
  import top from "./components/top.vue";
  import heroSection from "./components/heroSection.vue";
  import serveSection from "./components/serveSection.vue";
  import quemUsaBmw from "./components/quemUsaBmw.vue";
  import drAlexandre from "./components/drAlexandre.vue";
  import plataformaBmw from "./components/plataformaBmw.vue";
  import pqUsarBmw from "./components/pqUsarBmw.vue";
  import precosBmw from "./components/precosBmw.vue";
  import perguntas from "./components/perguntas.vue";
  // import formasDePagSeguro from "./components/formasdepagesiteseguro.vue";
</script>

<template>
  <top/>
  <main class="main">
    <heroSection/>
    <serveSection/>
    <quemUsaBmw/>
    <drAlexandre/>
    <plataformaBmw/>
    <pqUsarBmw/>
    <precosBmw/>
    <perguntas/>
    <precosBmw/>
    <!-- <div class="pb-4">
      <formasDePagSeguro/>
    </div> -->
  </main>
   <!-- Scroll Top -->
   <a href="#" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center"><i
      class="bi bi-arrow-up-short"></i></a>

    <!-- Preloader -->
    <div id="preloader"></div>
</template>
