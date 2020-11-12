<template>
  <Wrapper></Wrapper>
</template>

<script>
import Wrapper from "./components/Wrapper.vue";

export default {
  name: "App",
  components: {
    Wrapper,
  },
};
</script>

<style>
* {
  padding: 0;
  margin: 0;
}

html {
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: inherit;
}
</style>
