<template>
  <div class="reveal">
    <div class="slides">
      <section>
        <h1>Donskoy</h1>
        <img src="../assets/presentacion-3000.gif" alt="" srcset="" style="
        position: absolute; 
  left: 0; 
  right: 0; 
  bottom: 0;
  top: 0;
  margin-inline: auto; 
  width: 70%;
">
        <h5 style="margin-top: 20%;">"La desfragmentacion del ecosistema movil"</h5>
        <h6 style="margin-top: 20%;">Integrantes: Gabriel Solotorevsky, Gustavo Benitez, Salvador Avalos</h6>
      </section>

      <section>
        <section>
          <div style="display: flex;text-align: center; justify-content: center; align-items: center;">

          <div>
            <p>
              Que harias si...
            </p>
          </div>
          <div>
          <img src="../assets/celular.svg" alt="">
          </div>
          <div>
            <p>
              Tu celular...
            </p>
          </div>

          </div>

        </section>
        <section>
          <div style="display: flex;text-align: center; justify-content: center; align-items: center;">

          <div>
            <p>
              Dejara
            </p>
          </div>
          <div>
          <img src="../assets/celular_roto.svg" alt="">
          <h1 style="position: absolute; top: 25%;left: 42%;">DE</h1>
          </div>
          <div>
            <p>
             funcionar
            </p>
          </div>

          </div>
        </section>
        <section>
          <h3>La verdad es que</h3>
          <p style="font-size: 20px;">la reparacion</p>
           <div style="display: flex;text-align: center; justify-content: center;">
          <div style="display: flex;justify-content:end; flex-direction: column; align-items: center;">
                      <v-icon icon="mdi-tag-search" color="#eee8d5" />
            <p>...o no muy accesible</p>

          </div>
          <div style="flex-grow: 1;">
          <img src="../assets/celular_roto.svg" alt="">
          </div>
          <div>
            
                      <h1>$</h1>
                      <p>Suele ser costosa...</p>
          
                    </div>

          </div>
        </section>
        <section>
          <img src="../assets/celular_frente.svg" alt="">
          <p>Llevandonos a comprar uno nuevo</p>
        </section>
        <section>
          <img src="../assets/celular_frente_componentes.svg" alt="">
        </section>
        <section>
          <img src="../assets/celular_frente_componentes_candado.svg" alt="">
        </section>
      </section>
      <section>
        <section>
          <div style="display: flex;justify-items: center;">

          <div style="background-color: blue;flex-grow: 1;transform: rotateX(20deg) rotateY(-40deg);">
            <div style="height: 50%;"><p>50%</p></div>
            <hr>
            <div style="height: 50%;"><p>Intel</p></div>
          </div>
          <div style="flex-grow: 1;">
            //TODO: cosa?
          </div>
          <div style="background-color: red;flex-grow: 1;transform: rotateX(20deg) rotateY(40deg);">
            <div style="height: 50%;"><p>50%</p></div>
            <hr>
            <div style="height: 50%;"><p>AMD</p></div>
          </div>

          </div>
        </section>
        <section>
          <img src="../assets/pc2.svg" alt="">
        </section>
        <section>
          <img src="../assets/celular_smg.svg" alt="">
        </section>
        <section>
          <img src="../assets/celular_muchos.svg" alt="">
        </section>
        <section>
          <img src="../assets/celular_muchos2.svg" alt="" width="50%">
        </section>
      </section>
      <section>
        <section>
          <img src="../assets/desarmado.svg" alt="" width="50%">
        </section>
        <section>
          <img src="../assets/donskoy.svg" alt="" width="50%">
        </section>
        <section>
          <img src="../assets/repo.svg" alt="" width="50%">
        </section>
        <section>
          <img src="../assets/repo_libre.svg" alt="" width="50%">
        </section>
      </section>
      <section>
        <img src="../assets/filosofia.svg" alt="">
      </section>
      <section>
        <section>
          <img src="../assets/impacto.svg" alt="">
        </section>
        <section>
          <img src="../assets/celular_kde.svg" alt="">
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