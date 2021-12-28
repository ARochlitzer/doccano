<template>
  <v-container fluid>
    <slot name="header" />
    <v-row justify="center">
      <v-col cols="12">
        <slot name="content" />
      </v-col>
    </v-row>
  </v-container>
</template>
