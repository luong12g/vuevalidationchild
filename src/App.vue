<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <h1>Child Component validation with Vuelidate</h1>
    <form-component />
  </div>
</template>

<script>
import FormComponent from "./components/FormComponent.vue";

export default {
  name: "App",
  components: {
    FormComponent
  }
};
</script>
