<template>
  <v-app>
     <v-app-bar app class="navbar">

      <v-app-bar-nav-icon @click="drawer = ! drawer"></v-app-bar-nav-icon>
      <v-toolbar-title>HCI Report</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-toolbar-items>
        <v-btn text>Team members</v-btn>
      </v-toolbar-items>
    </v-app-bar>
    <v-navigation-drawer
          class="deep-purple accent-4"
          dark
          app
          v-model="drawer"
        >
        <v-list>
          <v-list-item
            v-for="item in items"
            :key="item.title"
            link
            :href="item.link"
          >
            <v-list-item-content>
              <v-list-item-title>{{ item.title }}</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-list>

      </v-navigation-drawer>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  data: () => ({
    drawer:true,
     items: [
          { title: 'Home', link: 'title' },
          { title: 'About', link: 'style' },
        ]
  }),
};
</script>
<style  scoped>
.navbar{
  max-height :70px;
}
</style>