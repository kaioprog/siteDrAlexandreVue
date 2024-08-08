<script setup>
  import formasDePagEsiteSeguro from './formasDePagEsiteSeguro.vue';
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
            <h2 class="mt-1">Assinatura anual</h2>
            <!-- <p class="description">
                Ullam mollitia quasi nobis soluta in voluptatum et sint palora
                dex strater
              </p> -->
            <h6>12x de R$ 40,06</h6>
            <h6>Ou</h6>
            <h6>R$ 399<span> / ano</span></h6>
            <a
              href="https://pay.kiwify.com.br/ck7KKX8"
              target="_blank"
              class="cta-btn"
              >Escolher plano anual <i class="bi bi-hand-index-thumb"></i
            ></a>
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
            <h2>Assinatura semestral</h2>
            <!-- <p class="description">
                Ullam mollitia quasi nobis soluta in voluptatum et sint palora
                dex strater
              </p> -->
            <h6>12x de R$ 51,49</h6>
            <h6>Ou</h6>
            <h6>R$ 279<span> / 6 meses</span></h6>
            <a
              href="https://pay.kiwify.com.br/OyxDP4A"
              target="_blank"
              class="cta-btn"
              >Escolher plano semestral <i class="bi bi-hand-index-thumb"></i
            ></a>
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
            <h2>Assinatura mensal</h2>
            <!-- <p class="description">
                Ullam mollitia quasi nobis soluta in voluptatum et sint palora
                dex strater
              </p> -->
            <h6>R$ 59,90<span> / mês</span></h6>
            <a
              href="https://pay.kiwify.com.br/q03V8kv"
              target="_blank"
              class="cta-btn"
              >Escolher plano mensal <i class="bi bi-hand-index-thumb"></i
            ></a>
          </div>
        </div>
        <!-- End Pricing Item -->
      </div>
    </div>
    <formasDePagEsiteSeguro/>
  </section>
</template>
