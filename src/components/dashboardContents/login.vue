<template>
  <v-container>
      <v-card>
          <v-container>
              LANDING PAGE
          </v-container>
      </v-card>
      <v-btn @click="move()">Next</v-btn>
  </v-container>
</template>

<script>
export default {
    methods:{
        move(){
            this.$router.push('/user')
        }
    },
}
</script>