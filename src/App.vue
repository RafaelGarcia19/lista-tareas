<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">
        <router-link :to="{ name: 'home' }">
          <v-img
            alt="R Logo"
            class="shrink mr-2"
            contain
            src="https://makeitsimple.io/LogoMayus.png"
            transition="scale-transition"
            width="12rem"
          />
        </router-link>
        <span class="headline d-none d-md-flex">Lista de tareas</span>
      </div>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
