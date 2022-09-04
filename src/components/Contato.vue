<template>
  <div>
    <section id="contact" class="py-3">
        <div class="container px-5 my-5">
          <h1 class="text-center py-2">Contato</h1>
            <p class="text-center headlinep">Quer nos encontrar? Acesse nossas redes sociais</p>
          <div class="row justify-content-center">
            <div class="col-lg-10">
             <div class="contato justify-content-center">
              <div class="redesocial">
                <h2>Instagram</h2>
                <a href="https://www.instagram.com/techforweb/" target="_blank">
                  <i class='bx bxl-instagram'></i></a>
              </div>
              <div class="redesocial">
                <h2>WhatsApp</h2>
                <a href="https://www.instagram.com/techforweb/" target="_blank">
                  <i class='bx bxl-whatsapp'></i></a>
              </div>
              <div class="redesocial">
                <h2>Github</h2>
                <a href="https://www.instagram.com/techforweb/" target="_blank">
                  <i class='bx bxl-github'></i></a>
              </div>
             </div>
            </div>
          </div>
        </div>
      </section>

  </div>
</template>

<script>
export default {
name: 'ContatoView',
}
</script>

<style lang="scss">
/* css */

.contato{
  display: flex;
  color: #fff;
}
.contato .redesocial{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 30px;
}
.contato .redesocial a i{ 
margin-left: 10px;
color: #fff;
font-size: 30px;
transition: all 400ms ease;
}

.contato .redesocial a i:hover{ 
margin-left: 10px;
color: $primary;
}


</style>