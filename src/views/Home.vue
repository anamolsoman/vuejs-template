<template>
  <v-container>
    <section>
      <Contact />
      <Map />
    </section>
  </v-container>
</template>

<script>
// @ is an alias to /src
import Contact from "@/components/Contact.vue";
import Map from "@/components/Map.vue";

export default {
  name: "home",
  components: {
    Contact,
    Map
  }
};
</script>
