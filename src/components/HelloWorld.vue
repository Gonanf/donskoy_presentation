<template>
  <div class="reveal">
    <div class="slides">
      <section>
        <h1>Donskoy</h1>
        <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/presentacion-3000.gif" alt="" srcset="" style="
        position: absolute; 
  left: 0; 
  right: 0; 
  bottom: 0;
  margin-inline: auto; 
  width: 70%;
">
        <h6 style="margin-top: 20%;">Integrantes: Gabriel Solotorevsky, Gustavo Benitez, Salvador Avalos</h6>
      </section>

      <section>
        <section>
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular.svg" alt="">

        </section>
        <section>
          <div style="width: 100%;">
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_roto.svg" alt="">
            
          </div>
        </section>
        <section>
          <h1 style="float: right;">$</h1>
          <div style="width: 100%;">
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_roto.svg" alt="">
            
          </div>
          <v-icon icon="mdi-tag-search" style="float: left;" color="#eee8d5"/>
        </section>
        <section>
            <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_frente.svg" alt="">
        </section>
        <section>
            <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_frente_componentes.svg" alt="">
        </section>
        <section>
            <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_frente_componentes_candado.svg" alt="">
        </section>
      </section>
      <section>
        <section>
            <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/pc.svg" alt="">
        </section>
        <section>
            <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/pc2.svg" alt="">
        </section>
        <section>
            <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_smg.svg" alt="">
        </section>
        <section>
            <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_muchos.svg" alt="">
        </section>
        <section>
            <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_muchos2.svg" alt="" width="50%">
        </section>
      </section>
      <section>
        <section>
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/desarmado.svg" alt="" width="50%">
        </section>
        <section>
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/donskoy.svg" alt="" width="50%">
        </section>
        <section>
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/repo.svg" alt="" width="50%">
        </section>
        <section>
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/repo_libre.svg" alt="" width="50%">
        </section>
      </section>
      <section>
        <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/filosofia.svg" alt="">
      </section>
      <section>
        <section>
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/impacto.svg" alt="">
        </section>
        <section>
          <img src="/run/media/chaos/terciario/proyectos/donskoy_presentation/src/assets/celular_kde.svg" alt="">
        </section>
      </section>
    </div>
  </div>
</template>

<script setup>
import { onMounted } from 'vue';
import Reveal from 'reveal.js';
import Markdown from 'reveal.js/plugin/markdown/markdown.esm.js';

onMounted(() => {
  let deck = new Reveal({
    plugins: [Markdown],
  });
  deck.initialize();
});
</script>