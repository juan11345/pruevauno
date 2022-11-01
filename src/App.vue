<template>
  <v-app>
    <v-main>
      <Catalogo1 mensaje1="Hola Mundo"/>
      <Catalogo2/>
      <Catalogo4/>
      <Catalogo5/>
    </v-main>
  </v-app>
</template>

<script>
import Catalogo1 from './components/CatalogoNumero1.vue'
import Catalogo2 from './components/CatalogoNumero2.vue'
import Catalogo4 from './components/CatalogoNumero4.vue'
import Catalogo5 from './components/CatalogoNumero5.vue'

export default {
  name: 'App',

  components: {
    Catalogo1,
    Catalogo2,
    Catalogo4,
    Catalogo5,
  },

  data: () => ({
    //
  }),
};
</script>
