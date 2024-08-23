<script setup>
import {ref} from "vue"
const larguraTela = ref(screen.width)
</script>

<template>
  <header id="header" class="header d-flex align-items-center fixed-top" style="background-color: #050a30;">
    <div
      class="container-fluid container-xl position-relative d-flex align-items-center"
    >
      <a href="/" class="logo d-flex align-items-center me-auto">
        <!-- <img src="assets/img/logo.png" alt="" /> -->
        <span class="circle" style="margin-right: 13px; margin-bottom: 10px;"><span :style="larguraTela < 600 ? 'margin-left: 18px;margin-top: 5px; fonte-size:20px' : 'margin-left: 18px;margin-top: 5px'">Dr.</span></span>
        <h1 class="sitename" :style="larguraTela < 600 ? 'color: #63b2af; font-size: 20px':  'color: #63b2af; font-size: 24px'">
          Alexandre Mota
        </h1>
      </a>

      <!-- NAV -->
      <a class="btn-getstarted text-center" href="/#pricing" :style="larguraTela < 600 ? 'font-size:11px' :''">
        <b>QUERO SER ALUNO BMV</b>
        <img src="/src/assets/img/bmv/maoClique.svg" class="mao" alt="Ícone de Mãozinha">
      </a>
    </div>
  </header>
</template>
