<template>

  <v-layout column>
    <v-flex xs12 sm8 md6>
  <v-form v-model="valid">
    <v-text-field
      label="Name"
      v-model="name"
      :rules="nameRules"
      :counter="10"
      required
    ></v-text-field>
    <v-text-field
      label="E-mail"
      v-model="email"
      :rules="emailRules"
      required
    ></v-text-field>
  </v-form>
    </v-flex>
  </v-layout>
</template>

<script>
import draggable from 'vuedraggable'


</script>

 