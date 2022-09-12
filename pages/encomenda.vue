<template>
  <section class="section">
    

    <div class="columns">
      <div class="column is-4">
  
      </div>
      
      <div class="column is-4" style="background-color: #E1E1E2">
        
        <h1 class="title"> O seu BMW está à sua espera. </h1>
        
        <b-field label="Nome completo">
          <b-input v-model="name">Nome</b-input>
        </b-field>

        <b-field label="E-mail">
          <b-input v-model="email">@</b-input>
        </b-field>

        <b-field label="Modelo">
          <b-select placeholder="Modelo" icon="car">
            <optgroup label="Standard">
              <option value="1">Série 1</option>
              <option value="X3">X3</option>
            </optgroup>
            <optgroup label="Plug-in Híbridos">
              <option value="3">Série 3</option>
              <option value="5">Série 5</option>
              <option value="7">Série 7 </option>
            </optgroup>
          </b-select>
        </b-field>

                <b-field label="Cor">
          <b-select placeholder="Cor" icon="paint">
            <optgroup label="Padrão">
              <option value="Azul">Azul</option>
              <option value="Branco">Branco</option>
            </optgroup>
            <optgroup label="Individual Order*">
              <option value="Green">São Paulo Green</option>
              <option value="Blue">Miami Blue</option>
              <option value="Blau">Orient Blau </option>
            </optgroup>
          </b-select>
        </b-field>



        <b-field label="Informe a Capital (cidade) mais próxima de você">
          <b-input v-model="name">nome</b-input>
        </b-field>

        <div class="buttons">
           <button class="button is-primary">Solicitar orçamento</button>
        </div>

        
      </div>

      
       <div class="column is-4">
  
      </div>
      

    </div>

  
    
  </section>
</template>