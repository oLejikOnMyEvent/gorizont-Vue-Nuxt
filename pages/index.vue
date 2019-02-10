<template>
 <div>
   <v-carousel hide-delimiters>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel>
 
 
   <div class="findYourEstate" >
    <v-subheader light>НАЙДИТЕ ВАШУ НЕДВИЖИМОСТЬ</v-subheader>
 </div>
 
 
 
 <div class="filter">

  
  
 <v-layout justify-center>

 

   

    <v-flex lg8>
      <v-window
        v-model="window"
        class="elevation-1"
        vertical
      >
        <v-window-item
          v-for="n in length"
          :key="n"
        >
          <v-card flat>
            <v-card-text>
              <v-layout align-center mb-3>
                   

             <v-flex lg2>
        <v-select
          :items="items"
          label="Квартры"
          solo
        ></v-select>
      </v-flex>

          <v-flex lg2>
        <v-select
          :items="items"
          label="Комнаты"
          solo
        ></v-select>
      </v-flex>

         <v-flex lg2>
        <v-select
          :items="items"
          label="Дома"
          solo
        ></v-select>
      </v-flex>

<v-flex lg4>
        <v-select
          :items="items"
          label="Земельные участки"
          solo
        ></v-select>
      </v-flex>

      <v-flex lg2>
        <v-select
          :items="items"
          label="Гаражи"
          solo
        ></v-select>
      </v-flex>

      <v-flex lg3>
        <v-select
          :items="items"
          label="Для бизнеса"
          solo
        ></v-select>
      </v-flex>
      
</v-layout> 
     

      
            </v-card-text>
          </v-card>
        </v-window-item>
      </v-window>
    </v-flex>
  
  </v-layout>
</div>
 
 <div class="DopFilters">
   <v-layout justify-center>
   <v-flex lg8 >
<v-expansion-panel >
    <v-expansion-panel-content
      v-for="(item,i) in 1"
      :key="i"
    >
      <div slot="header" justify-center>Дополнительные фильтры</div>
      <v-layout justify-center>
        <v-flex lg4>
        <v-select
          :items="items"
          label="хаты"
          solo
        ></v-select>
      </v-flex>
        <v-flex lg4>
        <v-select
          :items="items"
          label="еще хаты"
          solo
        ></v-select>
      </v-flex>
      </v-layout>
    </v-expansion-panel-content>
  </v-expansion-panel>
  </v-flex>
  </v-layout>
 </div>

 <div class="cards">
<v-layout justify-center>
  <v-flex  lg2>
    <router-link to="/object">
<v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="200"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
          <div class="d-flex">
            <v-rating
              :value="value"
              color="amber"
              dense
              half-increments
              readonly
              size="14"
            ></v-rating>
            <div class="ml-2 grey--text text--darken-2">
              <span>{{ value }}</span>
              <span>({{ reviews }})</span>
            </div>
          </div>
        </div>
        <v-spacer></v-spacer>
        <v-btn icon class="mr-0">
          <v-icon>mdi-chevron-right</v-icon>
        </v-btn>
      </v-card-title>
    </v-card>
  </v-hover>
</router-link>
  </v-flex>

  <v-flex lg2>
<v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="200"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
          <div class="d-flex">
            <v-rating
              :value="value"
              color="amber"
              dense
              half-increments
              readonly
              size="14"
            ></v-rating>
            <div class="ml-2 grey--text text--darken-2">
              <span>{{ value }}</span>
              <span>({{ reviews }})</span>
            </div>
          </div>
        </div>
        <v-spacer></v-spacer>
        <v-btn icon class="mr-0">
          <v-icon>mdi-chevron-right</v-icon>
        </v-btn>
      </v-card-title>
    </v-card>
  </v-hover>

  </v-flex>

  <v-flex lg2>
<v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="200"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
          <div class="d-flex">
            <v-rating
              :value="value"
              color="amber"
              dense
              half-increments
              readonly
              size="14"
            ></v-rating>
            <div class="ml-2 grey--text text--darken-2">
              <span>{{ value }}</span>
              <span>({{ reviews }})</span>
            </div>
          </div>
        </div>
        <v-spacer></v-spacer>
        <v-btn icon class="mr-0">
          <v-icon>mdi-chevron-right</v-icon>
        </v-btn>
      </v-card-title>
    </v-card>
  </v-hover>

  </v-flex>

  <v-flex lg2>
    
<v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="200"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
        
      ></v-img>
      
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
          <div class="d-flex">
            <v-rating
              :value="value"
              color="amber"
              dense
              half-increments
              readonly
              size="14"
            ></v-rating>
            <div class="ml-2 grey--text text--darken-2">
              <span>{{ value }}</span>
              <span>({{ reviews }})</span>
            </div>
          </div>
        </div>
        <v-spacer></v-spacer>
        <v-btn icon class="mr-0">
          <v-icon>mdi-chevron-right</v-icon>
           
        </v-btn>
      </v-card-title>
    </v-card>
  </v-hover>

  </v-flex>

  <v-flex lg2>
<v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="200"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
          <div class="d-flex">
            <v-rating
              :value="value"
              color="amber"
              dense
              half-increments
              readonly
              size="14"
            ></v-rating>
            <div class="ml-2 grey--text text--darken-2">
              <span>{{ value }}</span>
              <span>({{ reviews }})</span>
            </div>
          </div>
        </div>
        <v-spacer></v-spacer>
        <v-btn icon class="mr-0">
          <v-icon>mdi-chevron-right</v-icon>
        </v-btn>
      </v-card-title>
    </v-card>
  </v-hover>

  </v-flex>

  <v-flex lg2>
<v-hover>
    <v-card
      slot-scope="{ hover }"
      :class="`elevation-${hover ? 12 : 2}`"
      class="mx-auto"
      width="200"
    >
      <v-img
        :aspect-ratio="16/9"
        src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
      ></v-img>
      <v-card-title>
        <div>
          <span class="headline">Cafe Badilico</span>
          
        </div>
        <v-btn icon class="mr-0">
          <v-icon>mdi-chevron-right</v-icon>
        </v-btn>
      </v-card-title>
    </v-card>
  </v-hover>

  </v-flex>

</v-layout>

 </div>

 <v-footer class="pa-3">
    <v-spacer></v-spacer>
    <div>&copy; {{ new Date().getFullYear() }}</div>
  </v-footer>
     <nuxt/>

 </div>
      
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: '/images/gorizont1.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg'
          }
        ],
        length: 3,
        window: 0,
        reviews: 413,
        value1: [30, 60],
        value2: [0, 40],
        value3: [110, 440]
      }
    }
  }
</script>

<style>
.cards{
  margin-top: 10px;
}
.filter{
  margin-top:5px
}
.findYourEstate{
  display: flex;
  justify-content: center;  
}

</style>
