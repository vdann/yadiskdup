<template>
  <v-app>
    <v-app-bar
      app
      color="grey lighten-4"
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />

        <h2>
          YaDiskDup
        </h2>

<!--
        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
-->
      </div>

      <v-spacer></v-spacer>


      <v-btn
        href="https://disk.yandex.ru/"
        target="_blank"
        text
      >
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="/yadisk.png"
          transition="scale-transition"
          width="40"
        />
        <span class="mr-2">Яндекс.Диск</span>
      </v-btn>
    </v-app-bar>

    <v-content>
      <YaDiskTree/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import YaDiskTree from './components/YaDiskTree';

export default {
  name: 'App',

  components: {
    // eslint-disable-next-line
    HelloWorld,
    YaDiskTree
  },

  data: () => ({
    //
  }),
};
</script>
