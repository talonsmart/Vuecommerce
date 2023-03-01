<template>
  <div class="checkout">
    <modal
      :header="'Checkout'"
      :isShow="showModal"
      v-if="showModal"
      @close="showModal = false"
    ></modal>
  </div>
</template>

<script>
import Modal from "../shared/Modal";
export default {
  name: "checkout",
  components: { Modal },
  data() {
    return {
      showModal: false,
    };
  },
  methods: {
    isCheckoutGroup() {
        if (this.showModal === true) {
            return 0
        }

        return 1
    }
  },
};
</script>

<style lang="css"></style>
