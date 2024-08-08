<script setup>
    import {ref} from "vue"
    const larguraTela = ref(screen.width)
</script>
<template>
    <div class="d-flex mt-5 container" style="flex-direction: column;align-items: center;">
        <div class="mb-3" :class="larguraTela < 600 ? 'w-100' : ''">
            <img width="700" :class="larguraTela < 600 ? 'w-100' : ''" src="../assets/img/bmv/formasDePagamento.png" alt="">
        </div>
        <div :class="larguraTela < 600 ? 'w-100' : ''">
            <img width="400" :class="larguraTela < 600 ? 'w-100' : ''" src="../assets/img/bmv/siteSeguro.png" alt="">
        </div>
    </div>
</template>