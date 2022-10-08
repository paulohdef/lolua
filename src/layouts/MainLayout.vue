<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="bg-pink-2 flex items-center justify-center" elevated>
          <div>
            <img src="../assets/logo.png" style="width: 200px">
           </div>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>

export default {
  name: 'MainLayout',
  components: {

  },
  data () {
    return {
      leftDrawerOpen: false,
      essentialLinks: linksData
    }
  }
}
</script>
