<script setup>
    import {ref} from "vue"
    const larguraTela = ref(screen.width)
</script>
<template>
    <div class="m-2">
    <div class="d-flex mt-5 container" style="flex-direction: column;align-items: center; background-color: white; border-radius: 20px;">
        <div class="mb-3" :class="larguraTela < 600 ? 'w-100' : ''">
            <img width="700" :class="larguraTela < 600 ? 'w-100' : ''" src="../assets/img/bmv/formasDePagamento.png" alt="">
        </div>
        <div :class="larguraTela < 600 ? 'w-100' : ''">
            <img width="400" :class="larguraTela < 600 ? 'w-100' : ''" src="../assets/img/bmv/siteSeguro.png" alt="">
        </div>
    </div>
</div>
</template>