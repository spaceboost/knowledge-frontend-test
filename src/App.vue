<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Knowledge</span>
        <span class="font-weight-light">TEST</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        flat
        href="https://spaceboost.com"
        target="_blank"
      >
        <span class="mr-2">Spaceboost</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <UserList/>
    </v-content>
  </v-app>
</template>

<script>
import UserList from './components/user/List'

export default {
  name: 'App',
  components: {
    UserList
  },
  data () {
    return {
      //
    }
  }
}
</script>