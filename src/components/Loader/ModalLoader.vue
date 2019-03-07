<template>
    <v-dialog
      v-model="show"
      hide-overlay
      persistent
      width="300"
    >
      <v-card
      >
        <v-card-text>
          <v-img src="/static/img/logo-03.png" height="40" contain />
          <v-progress-linear
            indeterminate
            color="primary"
            class="mb-0"
          ></v-progress-linear>
        </v-card-text>
      </v-card>
    </v-dialog>
</template>

<script>
  export default {
    data () {
    return {
      show:true
    }
  },
}
</script>
