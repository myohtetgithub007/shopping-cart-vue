<template>
  <div>
    <h2>This is test vue how {{ name }}</h2>
    <slot></slot>
  </div>
</template>
<script>
export default {
  props: ["name"],
  name: "Test",
};
</script>
