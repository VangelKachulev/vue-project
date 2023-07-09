<template>
  <h1 class="haha">{{ msg }}</h1>
</template>

<script>
export default {
  name: "FirstOne",
  props: {
    msg: String,
  },
};
</script>

<style>
.haha {
  color: red;
}
</style>
