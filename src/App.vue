<template>
  <v-app>
    <v-content>
      <CasesTracker />
    </v-content>
  </v-app>
</template>

<script>
import CasesTracker from "./components/CasesTracker";

export default {
  name: "App",

  components: {
    CasesTracker
  }
};
</script>
