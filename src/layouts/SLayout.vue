
<template>
  <q-layout view="hHh LpR fFf">

    <q-header reveal elevated class="bg-blue-6 text-white " height-hint="98">
      <q-toolbar v-if="$q.platform.is.desktop">
        <q-toolbar-title align="center" class="text-h4 text-weight-bold">
          <q-avatar>
            <!-- <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg"> -->
          </q-avatar>
          Arsip Tata Kelola  Administrasi
        </q-toolbar-title>
      </q-toolbar>

      <q-toolbar v-if="$q.platform.is.mobile">
        <q-toolbar-title align="left" class="text-h6 text-weight-bold">
          <q-avatar>
            <!-- <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg"> -->
          </q-avatar>
          Arsip Tata Kelola  Administrasi
        </q-toolbar-title>
      </q-toolbar>

<q-toolbar v-if="$q.platform.is.desktop">
        <q-toolbar-title align="center" class="text-h6 text-weight-bold">
          <q-avatar>
            <!-- <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg"> -->
          </q-avatar>
          BPS Provinsi Sulawesi Tengah
        </q-toolbar-title>
      </q-toolbar>

      <q-toolbar v-if="$q.platform.is.mobile">
        <q-toolbar-title align="left" class="text-h6 text-weight-bold">
          <q-avatar>
            <!-- <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg"> -->
          </q-avatar>
          BPS Provinsi Sulawesi Tengah
        </q-toolbar-title>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer reveal elevated class="bg-grey-8 text-white">
      <q-toolbar>
        <q-toolbar-title>
          <!-- <q-avatar>
            <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg">
          </q-avatar> -->
           [ ] dengan  <span class="animate__animated animate__fadeIn animate__infinite text-red" > ❤ </span> di Palu
           Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>
                   </q-toolbar-title>
      </q-toolbar>
    </q-footer>

  </q-layout>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>
