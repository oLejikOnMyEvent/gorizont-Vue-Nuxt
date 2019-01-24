<template>
 <div>
      <v-carousel hide-delimiters>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel>
     <nuxt/>
 </div>
      
</template>

<script>
export default {
  data () {
    return { items: 'pics/gorizont.jpg' }
  }
}
</script>
