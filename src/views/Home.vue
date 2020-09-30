<template>
  <div class="home">
    <Top></Top>
    <Middle></Middle>
    <Bottom></Bottom>
  </div>
</template>

<script>
// @ is an alias to /src
import Top from "@/components/Top.vue";
import Middle from "@/components/Middle.vue";
import Bottom from "@/components/Bottom.vue";

export default {
  name: "Home",
  components: {
    Top,
    Middle,
    Bottom
  }
};
</script>
