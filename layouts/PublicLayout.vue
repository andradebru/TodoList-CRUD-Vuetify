<template>
  <v-main>
    <PageBar />
    <router-vue />
    <PageFooter />
  </v-main>
</template>

<script>
import PageBar from "@/components/PageBar.vue";
import PageFooter from "@/components/PageFooter.vue";

export default {
  data: () => ({}),
  components: {
    PageFooter,
  },
};
</script>
