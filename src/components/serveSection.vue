<template>
  <section id="services" class="services section">
    <!-- Section Title -->
    <div class="container section-title mb-3" data-aos="fade-up">
      <h2>Os exercícios fáceis do Bom Movimento todos os dias com você</h2>
      <!-- <p>
            Necessitatibus eius consequatur ex aliquid fuga eum quidem sint
            consectetur velit
          </p> -->
    </div>
    <!-- End Section Title -->
    <div class="container about">
      <div class="row gy-4">
        <div
          class="col-lg-6 about-images"
          data-aos="fade-up"
          data-aos-delay="200"
        >
          <video
            width="900"
            controls
            autoplay
            muted
            class="img-fluid"
            style="height: 100%"
          >
            <source src="/src/assets/videos/videoTop.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
          <!-- <img src="assets/img/features-1.jpg" class="img-fluid" alt=""> -->
        </div>
        <div class="col-lg-6">

       
        <div
          class="content"
          data-aos="fade-up"
          data-aos-delay="100"
          style="
            font-size: x-large;
            display: flex;
            flex-direction: column;
            background-color: white;
            padding: 1.5rem;
            border-radius: 20px;
          "
        >
          <div
            style="
              display: flex;
              flex-direction: column;
              align-items: flex-start;
            "
          >
            <h3 style="font-size: 1.6rem; margin-bottom: 2rem; color: #050a30">
              <i style="color: #050a30" class="bi bi-phone"></i> Tão fácil
              quanto curtir uma série no celular
            </h3>
            <h3 style="font-size: 1.6rem; margin-bottom: 2rem; color: #050a30">
              <i style="color: #050a30" class="bi bi-play-btn"></i> Use
              exercícios fáceis para:
            </h3>
          </div>
          <ul>
            <li>
              <i style="color: #050a30" class="bi bi-check-circle"></i>
              <span style="color: #050a30">Aliviar Dores</span>
            </li>
            <li>
              <i style="color: #050a30" class="bi bi-check-circle"></i>
              <span style="color: #050a30">Melhorar seu Movimento</span>
            </li>
            <li>
              <i style="color: #050a30" class="bi bi-check-circle"></i>
              <span style="color: #050a30">Ter mais Saúde</span>
            </li>
            <li>
              <i style="color: #050a30" class="bi bi-check-circle"></i>
              <span>Acelerar seu Tratamento</span>
            </li>
          </ul>

          <a class="btn-getstarted text-center" style="font-size: 19px;" href="/#pricing">
            <b>QUERO SER ALUNO BMV</b>
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
      </div>
    </div>
  </section>
</template>
