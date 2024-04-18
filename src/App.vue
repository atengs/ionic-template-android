<template>
  <ion-app>
    <ion-router-outlet />
  </ion-app>
</template>

<script lang="ts">
import { IonApp, IonRouterOutlet } from '@ionic/vue';

export default {
  components: {
    IonApp, IonRouterOutlet
  },

  data() {
    return {
      api_path: 'http://localhost:8000/'
    }
  }
}
</script>
