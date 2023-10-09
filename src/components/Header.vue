<template >
  <div class="wrapper_logo">
    Brooklyn Public Library
  </div>
  <nav>
    <ul>
      <li>About</li>
      <li>Favorites</li>
      <li>Coffee shop</li>
      <li>Contacts</li>
      <li>Library Card</li>
    </ul>
  </nav>
  <IconS_profile/>
</template>

<script>
import IconS_profile from "@/components/icons/IconS_profile.vue";

export default {
  name: 'Header',
  components: {IconS_profile},
};
</script>

<style scoped>

</style>
