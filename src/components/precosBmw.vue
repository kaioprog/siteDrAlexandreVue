<script setup>
import formasDePagEsiteSeguro from "./formasDePagEsiteSeguro.vue";
</script>
<template>
  <section id="pricing" class="pricing section light-background">
    <!-- Section Title -->
    <div class="container section-title" data-aos="fade-up">
      <h2>Escolha o melhor plano de assinatura pra você!</h2>
      <!-- <p>
          Necessitatibus eius consequatur ex aliquid fuga eum quidem sint
          consectetur velit
        </p> -->
    </div>
    <!-- End Section Title -->

    <div class="container">
      <div class="row gy-4">
        <div class="col-lg-4" data-aos="zoom-in" data-aos-delay="100">
          <div
            class="pricing-item text-center featured foco"
            style="
              display: flex;
              flex-direction: column;
              justify-content: space-between;
            "
          >
            <p class="popular">Recomendado</p>
            <h2 class="mt-1" style="color: #050a30">Assinatura anual</h2>
            <!-- <p class="description">
                Ullam mollitia quasi nobis soluta in voluptatum et sint palora
                dex strater
              </p> -->
            <h6 style="color: #050a30;font-weight: bold">R$ 40,06 POR MÊS</h6>
            <h6 style="color: #050a30">Ou</h6>
            <h6 style="color: #050a30">R$ 399<span> / ano</span></h6>
            <a
              class="btn-getstarted text-center mt-3"
              style="font-size: 19px"
              href="https://pay.kiwify.com.br/ck7KKX8"
              target="_blank"
            >
              <b>Escolher plano anual</b>
              <img
                src="/src/assets/img/bmv/maoClique.svg"
                style="
                  position: absolute;
                  /* top: 143%;
                right: 200px; */
                  transform: translateY(50%);
                  width: 40px;
                  height: 40x;
                  animation: piscar 1s infinite;
                "
                alt="Ícone de Mãozinha"
              />
            </a>
          </div>
        </div>
        <!-- End Pricing Item -->

        <div class="col-lg-4" data-aos="zoom-in" data-aos-delay="200">
          <div
            class="pricing-item featured text-center"
            style="
              display: flex;
              flex-direction: column;
              justify-content: space-between;
            "
          >
            <h2 style="color: #050a30">Assinatura semestral</h2>
            <!-- <p class="description">
                Ullam mollitia quasi nobis soluta in voluptatum et sint palora
                dex strater
              </p> -->
            <h6 style="color: #050a30;font-weight: bold">R$ 51,49 POR MÊS</h6>
            <h6 style="color: #050a30">Ou</h6>
            <h6 style="color: #050a30">R$ 279<span> / 6 meses</span></h6>
            <a
              class="btn-getstarted text-center mt-3"
              style="font-size: 19px"
              href="https://pay.kiwify.com.br/OyxDP4A"
              target="_blank"
            >
              <b>Escolher plano semestral</b>
              <img
                src="/src/assets/img/bmv/maoClique.svg"
                style="
                  position: absolute;
                  /* top: 143%;
                right: 200px; */
                  transform: translateY(50%);
                  width: 40px;
                  height: 40x;
                  animation: piscar 1s infinite;
                "
                alt="Ícone de Mãozinha"
              />
            </a>
          </div>
        </div>
        <!-- End Pricing Item -->

        <div class="col-lg-4" data-aos="zoom-in" data-aos-delay="200">
          <div
            class="pricing-item featured text-center"
            style="
              display: flex;
              flex-direction: column;
              justify-content: space-between;
            "
          >
            <h2 style="color: #050a30">Assinatura mensal</h2>
            <!-- <p class="description">
                Ullam mollitia quasi nobis soluta in voluptatum et sint palora
                dex strater
              </p> -->
            <h6 style="color: #050a30;font-weight: bold">R$ 59,90 POR MÊS</h6>
            <a
              class="btn-getstarted text-center mt-3"
              style="font-size: 19px"
              href="https://pay.kiwify.com.br/q03V8kv"
              target="_blank"
            >
              <b>Escolher plano mensal</b>
              <img
                src="/src/assets/img/bmv/maoClique.svg"
                style="
                  position: absolute;
                  /* top: 143%;
                right: 200px; */
                  transform: translateY(50%);
                  width: 40px;
                  height: 40x;
                  animation: piscar 1s infinite;
                "
                alt="Ícone de Mãozinha"
              />
            </a>
          </div>
        </div>
        <!-- End Pricing Item -->
      </div>
    </div>
    <formasDePagEsiteSeguro />
  </section>
</template>
