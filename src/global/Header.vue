<template>
  <div>
    <v-app-bar app color="primary" dark>
      <v-spacer></v-spacer>

      <v-btn color="error" @click="deleteLocalStrage">一括削除</v-btn>
    </v-app-bar>
  </div>
</template>

<script>
export default {
    name: 'Header',
    methods: {
        deleteLocalStrage() {
            this.$emit('delete-local-strage')
        }
    }

}
</script>


<style>

</style>