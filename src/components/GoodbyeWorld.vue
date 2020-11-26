<template>
  <div class="hello">
    <h1>GOODBYE</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data: function() {
    return {
      debugInc: 0,
      message: this.msg,
    };

  }
};
</script>
