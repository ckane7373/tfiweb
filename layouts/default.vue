<template>
  <v-app dark class="pa-0 ma-0">
    <v-navigation-drawer
      v-model="drawer"
      :mini-variant="miniVariant"
      :clipped="clipped"
      expand-on-hover
      temporary
      fixed
      app
      dark
      class="grey lighten-4"
      width="160px"
    >
      <v-list>
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          :to="item.to"
          router
          exact
          class="pl-1 hovera ma-0"
        >
          <v-list-item-action>
            <v-icon class="grey--text darken-4">
              {{ item.icon }}
            </v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title
              class="grey--text darken-4 font-weight-bold"
              v-text="item.title"
            />
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-app-bar
      :clipped-left="clipped"
      height="40px"
      dense
      collapse-on-scroll
      hide-on-scroll="true"
      fixed
      app
      class="grey lighten-4"
    >
      <v-app-bar-nav-icon
        class="text--darken--2 grey--text"
        @click.stop="drawer = !drawer"
      />
      <v-spacer class="d-flex d-sm-none" />
      <v-btn icon @click.stop="rightDrawer = !rightDrawer">
        <v-icon class="blue--text text--darken--4">
          mdi-phone
        </v-icon>
      </v-btn>
      <v-spacer />
      <v-toolbar-title
        class="ml-2 blue--text text--darken--4 d-none d-sm-flex"
        v-text="title"
      />
      <v-btn class="grey--text text--darken--4" icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
    </v-app-bar>
    <v-main class="mx-1 pa-0 grey lighten-4">
      <v-container fluid>
        <nuxt />
      </v-container>
    </v-main>
    <v-navigation-drawer
      v-model="rightDrawer"
      app
      right
      light
      temporary
      fixed
      class="ma-0 pa-0 black"
      width="250px"
    >
      <contact />
    </v-navigation-drawer>
    <v-footer width="100%" class="ma-0 pa-0">
      <v-container fluid class="ma-0 pa-0">
        <v-row>
          <v-col><footercontact /></v-col>
        </v-row>
      </v-container>
      <v-container fluid>
        <v-row class="pa-0 ma-0">
          <v-col clos="12" class="py-1">
            <div class="text-xs-caption text-sm-caption strai">
              &copy; Copyright, all reserved 2010 -
              {{ new Date().getFullYear() }}
            </div>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
  </v-app>
</template>

<script>
import contact from '~/components/contact.vue'
import footercontact from '~/components/footercontact.vue'
export default {
  components: {
    contact,
    footercontact
  },
  data () {
    return {
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'TEN FORWARD INTERNATINAL G R O U P',
      dialog: false,
      clipped: true,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-home-outline',
          title: 'Home',
          to: '/'
        },
        {
          icon: 'mdi-briefcase-search-outline',
          title: 'Overview',
          to: '/overview'
        },
        {
          icon: 'mdi-handshake-outline',
          title: 'Businesses',
          to: '/businesses'
        },
        {
          icon: 'mdi-wrench-outline',
          title: 'Services',
          to: '/services'
        },
        {
          icon: 'mdi-cog-outline',
          title: 'Products',
          to: '/products'
        },
        {
          icon: 'mdi-account-hard-hat ',
          title: 'Projects',
          to: '/projects'
        },
        {
          icon: 'mdi-account-group-outline ',
          title: 'Partners',
          to: '/partners'
        },
        {
          icon: 'mdi-account-cog-outline',
          title: 'Careers',
          to: '/careers'
        },
        {
          icon: 'mdi-account-multiple-plus-outline',
          title: 'Contacts',
          to: '/contact'
        }
      ]
    }
  }
}
</script>

<style scoped>
</style>
