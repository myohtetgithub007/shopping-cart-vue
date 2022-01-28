<template>
  <div>
    <h1>Hello to the vue tutorial</h1>
    <Test />
  </div>
</template>
<script>
import Test from "./Test";
export default {
  components: { Test },
  name: "App",
};
</script>
//app componet calling test.vue component
