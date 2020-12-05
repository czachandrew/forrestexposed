<template>
  <div class="content">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <Announcement style="margin-top: 24px;" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Announcement from "@/components/Announcement.vue";

export default {
  name: "Home",
  components: {
    Announcement
  }
};
</script>

Announcement
