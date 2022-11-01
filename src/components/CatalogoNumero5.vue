<template>
    <div class="Catalogo5">
        <v-footer padless>
            <v-col
              class="text-center"
              cols="12"
            >
              {{ new Date().getFullYear() }} — <strong>Contactenos : 3138161844</strong>
            </v-col>
          </v-footer>
    </div>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        'mdi-home',
        'mdi-email',
        'mdi-calendar',
        'mdi-delete',
      ],
      items: [
        'default',
        'absolute',
        'fixed',
      ],
      padless: false,
      variant: 'default',
    }),
    computed: {
      localAttrs () {
        const attrs = {}

        if (this.variant === 'default') {
          attrs.absolute = false
          attrs.fixed = false
        } else {
          attrs[this.variant] = true
        }
        return attrs
      },
    },
  }
</script>

<style>
.parte-de-abajo{
    text-align: center;
}
</style>