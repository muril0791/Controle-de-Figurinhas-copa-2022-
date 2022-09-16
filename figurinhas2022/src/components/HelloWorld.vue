<template>
  <v-app id="inspire">
    <v-main>
      <v-container>
        <v-row>
          <v-col v-for="n in 24" :key="n" cols="3">
            <v-card height="300" width="250"></v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  //
};
</script>
