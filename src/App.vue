<template>
  <v-app>
    <v-main>
      <UsersList/>
    </v-main>
  </v-app>
</template>

<script>
import UsersList from './pages/UsersList.vue';

export default {
  name: 'App',
  components: {
    UsersList,
  },
  data() {
    return {};
  },
};
</script>
