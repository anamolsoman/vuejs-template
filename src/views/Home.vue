<template>
  <v-container>
    <section>
      <Contact :label_one="label_one" :label_two="label_two" />
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
  data() {
    return {
      label_one: "First Name",
      label_two: "Email",
      label_three: "Subject"
    };
  },
  components: {
    Contact,
    Map
  }
};
</script>
