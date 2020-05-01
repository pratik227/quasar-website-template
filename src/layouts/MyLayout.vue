<template>
  <q-layout view="lHh Lpr lFf" style="">
    <q-header elevated style="background:linear-gradient( 135deg, #699cc3 10%, #1a6bc3 100%)">
      <q-toolbar>
        <q-toolbar-title>
          Quasar App
        </q-toolbar-title>
        <div>Quasar v{{ $q.version }}</div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view/>
    </q-page-container>
  </q-layout>
</template>

<script>
    export default {
        name: 'MyLayout',

        data() {
            return {}
        }
    }
</script>
