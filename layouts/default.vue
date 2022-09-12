<template>
  <div class="container is-fluid">

    <b-navbar style = "height: 65px">
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img style = "max-height: 65px"
                src="https://i.pinimg.com/originals/39/02/47/3902471b2e48145bf70aba8759a88892.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template #start>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                Home
            </b-navbar-item>
            <b-navbar-item tag="router-link" :to="{ path: '/series' }">
                Séries
            </b-navbar-item>
                      <b-navbar-item tag="router-link" :to="{ path: '/teste' }">
                Teste
            </b-navbar-item>
        </template>

        <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-primary">
                        <strong>Registre-se</strong>
                    </a>
                    <b-navbar-item tag="router-link" :to="{ path: '/login' }">
                        Entrar
                    </b-navbar-item>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>

    <Nuxt/>

    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>Site protótipo</strong> by Felipe O. 
          <a target="_blank" href="https://fae.edu">FAE Centro Universitário</a>
        </p>
      </div>
    </footer>      
    
  </div>
</template>

