<template>
  <div>
    <h1>Hello to the vue tutorial {{ name }}</h1>
    <Test name="myohtet"> This is slot </Test>
  </div>
</template>
<script>
import Test from "./Test";
export default {
  components: { Test },
  name: "App",
};
</script>
//app componet calling test.vue component or nested component //slot and props
is used data carry to one component to another component //props is inside of
<Test></Test>

//slot is used in is eg This is slot
