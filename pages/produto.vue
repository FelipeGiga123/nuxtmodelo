<template>
  <section class="section">
    <h1 class="title">Faça sua encomenda</h1>
<div> 
    <div class="columns mt-4"> 
      <div class="column is-3">
        <figure class="image is-300x300">
          <img src="https://www.bmw.com.br/content/dam/bmw/common/all-models/1-series/5-door/2019/navigation/bmw-1-series-modelfinder.png">
        </figure>

      </div>

      
      <div class="column is-6">
      <div
        <h1 class="title is-1" style=background-color:#E1E12> Série 1</h1>

        <article class="message">
          
            <div class="message-body">
             Gasolina <strong> Activeflex </strong> <br>
             
            </div>
        </article>

        
      </div>
      

      
      <div class="column is-3 mt-4">
        <h1 class="title is-1  has-text-centered"> R$293.950</h1>
        <b-button tag="router-link" expanded :to="{ path: '/encomenda' }" type="is-primary">Orçamentos</b-button>
     
       
      </div>

     
    </div>

</div>   

  <div> 
    <div class="columns mt-4"> 
      <div class="column is-3">
        <figure class="image is-300x300">
          <img src="data:image/jpeg;base64,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">
        </figure>

      </div>

      
      <div class="column is-6">
      <div
        <h1 class="title is-1" style=background-color:#E1E12> Série 3</h1>

        <article class="message">
          
            <div class="message-body">
             Gasolina <strong> Plug-in Híbrido </strong> <br>
             
            </div>
        </article>

        
      </div>
      

      
      <div class="column is-3 mt-4">
        <h1 class="title is-1  has-text-centered"> R$ 298.950</h1>
        <b-button tag="router-link" expanded :to="{ path: '/encomenda' }" type="is-primary">Orçamentos</b-button>
     
       
      </div>

     
    </div>

</div>   

    <div> 
    <div class="columns mt-4"> 
      <div class="column is-3">
        <figure class="image is-300x300">
          <img src="https://www.bmw.com.br/content/dam/bmw/common/all-models/5-series/sedan/2021/Navigation/bmw-5-series-sedan-POSI-modelfinder.png">
        </figure>

      </div>

      
      <div class="column is-6">
      <div
        <h1 class="title is-1" style=background-color:#E1E12> Série 5</h1>

        <article class="message">
          
            <div class="message-body">
             Gasolina <strong> Active </strong> <br>
             
            </div>
        </article>

        
      </div>
      

      
      <div class="column is-3 mt-4">
        <h1 class="title is-1  has-text-centered"> R$450.950</h1>
        <b-button tag="router-link" expanded :to="{ path: '/encomenda' }" type="is-primary">Orçamentos</b-button>
     
       
      </div>

     
    </div>

</div>   

      <div> 
    <div class="columns mt-4"> 
      <div class="column is-3">
        <figure class="image is-300x300">
          <img src="https://www.bmw.com.br/content/dam/bmw/common/all-models/x-series/series-overview/bmw-x-series-overview-page-model-carousel-12.jpg.asset.1618384426673.jpg">
        </figure>

      </div>

      
      <div class="column is-6">
      <div
        <h1 class="title is-1" style=background-color:#E1E12> X3</h1>

        <article class="message">
          
            <div class="message-body">
             Gasolina <strong> Plug-in Híbrido </strong> <br>
             
            </div>
        </article>

        
      </div>
      

      
      <div class="column is-3 mt-4">
        <h1 class="title is-1  has-text-centered"> R$397.950</h1>
        <b-button tag="router-link" expanded :to="{ path: '/encomenda' }" type="is-primary">Orçamentos</b-button>
     
       
      </div>

     
    </div>

</div>   
  </section>
</template>
