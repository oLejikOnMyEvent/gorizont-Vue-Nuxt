<template>
    <v-app light>
          <v-footer class="pa-3">
      <v-spacer></v-spacer>
      <v-flex>
        created by
        <a href="https://github.com/oLejikOnMyEvent">Oleg osipov</a>
      </v-flex>
      <div>&copy; {{ new Date().getFullYear() }}</div>
    </v-footer>
    <nuxt/>
    </v-app>
</template>
