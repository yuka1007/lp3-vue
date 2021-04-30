<template>
  <div id="app"></div>
</template>

<script>
import axios from "axios";
export default {
  created() {
    axios.get("data.json").then((response) => console.log(response));
  },
};
</script>
