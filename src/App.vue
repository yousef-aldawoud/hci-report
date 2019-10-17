<template>
  <v-app>
     <v-app-bar app class="navbar">

      <v-app-bar-nav-icon @click="drawer = ! drawer"></v-app-bar-nav-icon>
      <v-toolbar-title>HCI Report</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-toolbar-items>
        <v-btn text @click="team = !team" v-if="!team">Team members</v-btn>
        <v-btn text @click="team = !team" v-else>Report</v-btn>
      </v-toolbar-items>
    </v-app-bar>
    <v-navigation-drawer
          class="deep-purple accent-4"
          dark
          app
          v-model="drawer"
        >
      
        <v-list v-if="!team"
          class="hidden-sm-and-down"
        >
          <v-list-item
            v-for="item in items"
            :key="item.title"
            link
            :href="item.link"
            
          >
            <v-list-item-content>
              <v-list-item-title >{{ item.title }}</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-list>
        <v-list v-if="!team">
          <v-list-item
            v-for="item in items"
            :key="'s'+item.title"
            link
            @click="drawer = !drawer"
            class="hidden-md-and-up"
            :href="item.link"
          >
            <v-list-item-content>
              <v-list-item-title >{{ item.title }}</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-list>
        <v-list v-else>
          <v-list-item @click="team=!team">Report</v-list-item>
        </v-list>
      </v-navigation-drawer>

    <v-content>
      <HelloWorld>
        <Report v-if="!team"/>
        <Team v-else/>
      </HelloWorld>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Report from './components/Report.vue';
import Team from './components/Team.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,Report,Team
  },
  data: () => ({
    team:false,
    drawer:true,
     items: [
          { title: 'Introduction', link: '#intro' },
          { title: 'Material', link: '#material' },
          { title: 'Methodology', link: '#methodology' },
          { title: 'Software insruction', link: '#insruction' },
          { title: 'Discussion & Findings', link: '#discussion' },
          { title: 'One way ANOVA', link: '#anova' },
          { title: 'Analysis', link: '#analysis' },
          { title: 'Further Research', link: '#further-research' },
          { title: 'Usability Testing', link: '#usability-testing' },
          { title: 'Usability Evaluation', link: '#usability-eval' },
          { title: 'Conclusion', link: '#conclusion' },
          { title: 'Individual Reflection', link: '#reflection' },
        ]
  }),
};
</script>
<style  scoped>
.navbar{
  max-height :70px;
}
</style>