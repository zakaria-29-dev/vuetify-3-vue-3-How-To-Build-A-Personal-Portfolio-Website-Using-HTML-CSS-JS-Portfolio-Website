<template>
  <v-footer>
      <v-card
        elevation="0"
        rounded="0"
        width="100%"
        class="bg-grey text-center"
      >
        <v-card-text>
          <v-btn
            class="mx-4"
            icon="fas fa-comment"
            variant="plain"
            color="white"
          ></v-btn>
          <v-btn
            class="mx-4"
            icon="fas fa-university"
            variant="plain"
            color="white"
          ></v-btn>
          <v-btn
            class="mx-4"
            icon="fas fa-wifi"
            variant="plain"
            color="white"
          ></v-btn>
          <v-btn
            class="mx-4"
            icon="fas fa-podcast"
            variant="plain"
            color="white"
          ></v-btn>
        </v-card-text>

        <v-card-text class="text-white">
          @ {{ new Date().getFullYear() }} —
          <strong>AAE IdeaPro All Rights Reserved</strong>
        </v-card-text>
      </v-card>
    </v-footer>
</template>

<script>
export default {

}
</script>

<style>
.v-footer {
  padding: 8px 0 !important;
}
</style>