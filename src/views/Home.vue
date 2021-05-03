<template>
  <the-header></the-header>
  <main-container></main-container>
  <the-footer></the-footer>
</template>

<script>
import theHeader from "./Header";
import mainContainer from "./MainContainer.vue";
import theFooter from "./Footer.vue";

export default {
  components: { theHeader, mainContainer, theFooter },
};
</script>

<style scoped></style>
