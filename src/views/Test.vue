<template>
  <div class="test">
    <h1>{{ message }}</h1>
  </div>
</template>

<style></style>

<script>
import Darkmode from "darkmode-js";

new Darkmode().showWidget();

export default {
  data: function () {
    return {
      message: "This is a test page",
    };
  },

  methods: {},
};
</script>
