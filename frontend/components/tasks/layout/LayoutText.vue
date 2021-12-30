<template>
  <v-container fluid>
    <slot name="header" />
    <v-row justify="center">
      <v-col cols="12" md="11">
        <slot name="content" />
      </v-col>
      <v-col cols="12" md="1">
        <slot name="sidebar" />
      </v-col>
    </v-row>
  </v-container>
</template>
