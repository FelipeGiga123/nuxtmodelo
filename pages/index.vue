<template>
  <section class="section">

 <!-- carousel com imagens -->
    <b-carousel class="colums mb-5">
      <b-carousel-item>
        <b-image class="image" :src="require('@/assets/1.jpgR.jpg')"></b-image>
      </b-carousel-item>
      <b-carousel-item>
        <b-image class="image" :src="require('@/assets/2.jpg')"></b-image>
      </b-carousel-item>      
      <b-carousel-item>
        <b-image class="image" :src="require('@/assets/3.jpg')"></b-image>
      </b-carousel-item>            
    </b-carousel>

    <h4 class="title is-4 is-black">Conquiste seu BMW e curta o puro prazer de dirigir</h4>
    
<div class="columns mt-4">
      <div class="column is-3">
        <article class="notification is-white has-text-centered">
          <b-image class="image" :src="require('@/assets/i3.jpg')"></b-image>
          <p class="title mt-5">Elétricos</p>
          <p class="subtitle">Conheça o I3</p>
           <b-button type="is-primary">Saiba mais</b-button>
        </article>
      </div>
      <div class="column is-3 has-text-centered">
        <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/m3.jpg')"></b-image>
          <p class="title mt-5">M Academy</p>
          <p class="subtitle">M3 à todo vigor</p>
          <b-button type="is-primary">Saiba mais</b-button>
        </article>
      </div>
      <div class="column is-3">
        <article class="notification is-white has-text-centered">
          <b-image class="image" :src="require('@/assets/sete.jpg')"></b-image>
          <p class="title mt-5">Luxo 7 estrelas</p>
          <p class="subtitle">O balanço perfeito</p>
           <b-button type="is-primary">Saiba mais</b-button>
        </article>
      </div>      
      <div class="column is-3">
        <article class="notification is-white has-text-centered">
          <b-image class="image" :src="require('@/assets/historia.jpg')"></b-image>
          <p class="title mt-5">História</p>
          <p class="subtitle is-gray">BMW Museum</p>
           <b-button type="is-primary">Saiba mais</b-button>
        </article>
      </div> 
    </div>  

    <section class="hero is-white">
            <div class="hero-body">
                <p class="title has-text-centered mb-6">
                    Deixe a tecnologia liderar
                </p>
              
<b-image class="image" :src="require('@/assets/3-Series-Banner (2).png')"></b-image>
            
            </div>
        </section>

    
  
  </section>
</template>

