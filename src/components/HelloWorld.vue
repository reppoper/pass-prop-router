<template>
  <div class="hello">
    <h1>HELLO</h1>
    <GoodbyeWorld :msg="myData" />
  </div>
</template>

<script>
import GoodbyeWorld from "./GoodbyeWorld.vue";

export default {
  name: "HelloWorld",
  components: {
    GoodbyeWorld,
  },
  data() {
    return {
      myData: "hello world",
    };
  },
};
</script>
