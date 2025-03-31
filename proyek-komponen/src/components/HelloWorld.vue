<template>
  <div>
    <HelloWorld msg="Halo, ini komponen HelloWorld!"/>
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld
  }
};
</script>
