<template>
  <v-app>
    <PageHeader/>
    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
import PageHeader from '@/components/Header.vue'
export default {
  name: 'app',
  components: {
    PageHeader
  }
}
</script>
