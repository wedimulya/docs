<template>
  <v-card class="secondary elevation-0">
    <v-card-text>
      <v-container fluid>
        <v-layout row>
          <v-flex xs4>
            <v-subheader class="grey--text text--lighten-1">Normal with hint text</v-subheader>
          </v-flex>
          <v-flex xs5>
            <v-text-field
              name="input-1-3"
              label="Hint Text"
              single-line
              light
              prepend-icon="phone"
            ></v-text-field>
          </v-flex>
          <v-flex xs3>
            <v-btn-dropdown v-bind:options="[{ text: 'Mobile' }]" label="Mobile" light></v-btn-dropdown>
          </v-flex>
        </v-layout>
        <v-layout row>
          <v-flex xs4>
            <v-subheader class="grey--text text--lighten-1">Focus</v-subheader>
          </v-flex>
          <v-flex xs5>
            <v-text-field
              name="input-2-3"
              label="Hint Text"
              class="input-group--focused"
              prepend-icon="phone"
              value="650"
              single-line
              light
            ></v-text-field>
          </v-flex>
          <v-flex xs3>
            <v-btn-dropdown v-bind:options="[{ text: 'Mobile' }]" label="Mobile" light></v-btn-dropdown>
          </v-flex>
        </v-layout>
        <v-layout row>
          <v-flex xs4>
            <v-subheader class="grey--text text--lighten-1">Normal with input text</v-subheader>
          </v-flex>
          <v-flex xs5>
            <v-text-field
              name="input-3-3"
              label="Hint Text"
              value="650-555-1234"
              prepend-icon="phone"
              single-line
              light
            ></v-text-field>
          </v-flex>
          <v-flex xs3>
            <v-btn-dropdown v-bind:options="[{ text: 'Mobile' }]" label="Mobile" light></v-btn-dropdown>
          </v-flex>
        </v-layout>
      </v-container>
    </v-card-text>
</v-card>
</template>
