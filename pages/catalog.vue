<template>
<div>

<v-container fluid>
<v-layout row wrap>


    <v-flex md3 class="selects" >
        <v-select
          :items="items"
          label="Solo field"
          solo
        ></v-select>
        <v-select
          :items="items"
          label="Solo field"
          solo
        ></v-select>
        <v-select
          :items="items"
          label="Solo field"
          solo
        ></v-select>
         <v-select
          :items="items"
          label="Solo field"
          solo
        ></v-select>
         <v-select
          :items="items"
          label="Solo field"
          solo
        ></v-select>
         <v-select
          :items="items"
          label="Solo field"
          solo
        ></v-select>
         <v-select
          :items="items"
          label="Solo field"
          solo
        ></v-select>
      </v-flex>

      

<v-flex md3>

 <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>

  <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>

  

  <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>
  </v-flex> 

  <v-flex md3>

     <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>
  <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>  

   <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>
  </v-flex>

  <v-flex md3>
  <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>

 <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>
  
  
   <v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="250"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
        </div>
      </v-card-title>
    </v-card>
  </v-hover>
  </v-flex>

  
 
  
</v-layout>


</v-container>




    

 

  

  
  
<nuxt/>
</div>
  </template>
<script>
export default {
  data () {
    return {
      price: 100
    }
  }
}
</script>

<style scope>
.selects{
}
</style>
