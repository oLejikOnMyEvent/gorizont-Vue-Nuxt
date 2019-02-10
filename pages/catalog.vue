<template>
<div>

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
           
              
              </v-layout>

              

             

              <v-flex lg2>
        <v-select
          :items="items"
          label="Solo field"
          solo
        ></v-select>
      </v-flex>
            </v-card-text>
          </v-card>
        </v-window-item>
      </v-window>
    </v-flex>
  </v-layout>





    

 

  

  
  
<nuxt/>
</div>
  </template>
<script>
  export default {
    data: () => ({
      length: 3,
      window: 0
    })
  }
</script>

<style scope>

</style>
