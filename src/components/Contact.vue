<template>
  <v-card class="col-md-6 col-sm-12 col-lg-4 text-center " id="contact-form">
    <v-form action="#" method="POST">
      <v-text-field type="text" :label="label_one" />
      <v-text-field type="email" :label="label_two" />
      <v-textarea name="Subject" label="Subject"></v-textarea>
      <v-btn class="success">submit</v-btn>
      <v-btn>clear</v-btn>
    </v-form>
  </v-card>
</template>

<script>
export default {
  name: "Contact",
  props: ["label_one", "label_two"],
  data() {
    return {};
  }
};
</script>
<style scoped>
/* #contact-form {
  margin-top: 200px;
  margin-left: 600px;
} */
</style>
