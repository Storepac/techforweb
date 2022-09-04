<template>
    <div class="main">
      <header class="container">
        <div class="logo">
          <h1>T4W</h1>
        </div>
       <div class="icons">
         <a href="https://www.instagram.com/techforweb/" target="_blank"><i class='bx bxl-instagram'></i></a>
        <i class='bx bxl-facebook-circle'></i>
        <a href="https://github.com/gsmatheus/" target="_blank"><i class='bx bxl-github'></i></a>
       </div>
      </header>
      <section id="section1" class="py-5">
        <div class="container">
        <div class="row ">
        <div class="intro">
          <!-- <h1>Olá sejam bem-vindos</h1> -->
          <div class="static ">
              <div class="txt-static">
              Nós somos
              </div>
              <div class="txt-dinamic">
                <ul>
                  <li><span>Desenvolvedores</span></li>
                  <li><span>Empreeendedores</span></li>
                  <li><span>Criativos</span></li>
                  <li><span>Designers</span></li>
                </ul>
              </div>
            </div>

          
            <div class="dinamic ">
              <div class="txt-static">
              Nós somos
              </div>
              <div class="txt-dinamic">
                <ul>
                  <li><span>Desenvolvedores</span></li>
                  <li><span>Empreeendedores</span></li>
                  <li><span>Criativos</span></li>
                  <li><span>Designers</span></li>
                </ul>
              </div>
            </div>
          </div>
      <!--   <div class="col-12 col-sm-12 col-md-4">
          <div class="infos">
            <div class="logo">
              <h1>T4W</h1>
            </div>
            <div class="txt-info">
              <a href="#" title="Confira nossos projetos" class="btn btn-box">
                <div class="reflexo"></div>
                <i class='bx bx-check-circle'></i>Confira nossos projetos
              </a>
            </div>
          </div>
        </div> -->
      </div>
      </div>
      </section>
      <SobreNos/>
      <NossaExperiencia/>
      <Oferecer/>
      <Projetos/>
      <Contato/>
      <Footer/>
    </div>
</template>

<script>
// @ is an alias to /src
import SobreNos from '@/components/SobreNos.vue'
import NossaExperiencia from '@/components/NossaExperiencia.vue'
import Oferecer from '@/components/Oferecer.vue'
import Projetos from '@/components/Projetos.vue'
import Contato from '@/components/Contato.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'HomeView',
  components: {
    SobreNos,
    NossaExperiencia,
    Oferecer,
    Projetos,
    Contato,
    Footer
},
  data() {
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
/* css */
</style>
