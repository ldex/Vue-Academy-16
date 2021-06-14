<template>
  <div class="home">
    <h2>Home!</h2>
    <img alt="Vue logo" src="../assets/logo.png" />
    <modal-button button-text="Open Modal!"></modal-button>
  </div>
</template>

<script>
import ModalButton from "@/components/ModalButton.vue";

export default {
  components: {
    ModalButton,
  },
};
</script>

<style lang="scss" scoped>
</style>