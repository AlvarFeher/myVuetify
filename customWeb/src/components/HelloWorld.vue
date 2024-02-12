<template>
  <div id="app">
    <div class="parent-container" style="display: flex; flex-direction: column;">
      <v-container class="titleBar" fluid style="background-color: #7dcfb6; display: flex; flex-direction: row;">
        <v-btn-group>
          <v-btn>Experience</v-btn>
          <v-btn>Education</v-btn>
          <v-btn>About me</v-btn>
          <v-btn>Projects</v-btn>
        </v-btn-group>
      </v-container>
      <div class="sections" fluid>
        <v-divider :thickness="8" class="border-opacity-100"></v-divider>
        <div class="currently">
          <v-card height="800" width="100%" style="font-size:100px ;">
            Hi, My name is Álvaro Feher
          </v-card>
        </div>
        <v-divider :thickness="8" class="border-opacity-100"></v-divider>
        <div class="currently">
          <v-card height="800" width="100%">
            Currently
          </v-card>
        </div>
        <v-divider :thickness="8" class="border-opacity-100"></v-divider>
        <div class="experience">
          <v-card height="100">
            experience
          </v-card>
        </div>
        <v-divider :thickness="8" class="border-opacity-100"></v-divider>
        <div class="education">
          <v-card height="100">
            education
          </v-card>
        </div>
        <v-divider :thickness="8" class="border-opacity-100"></v-divider>
        <div class="about me">
          <v-card height="100">
            about me
          </v-card>
        </div>
        <v-divider :thickness="8" class="border-opacity-100"></v-divider>
        <div class="projects">
          <v-card height="100">
            projects
          </v-card>
        </div>
      </div>
    </div>

  </div>
</template>

<script>

export default {
  data: () => ({
    items: [
      { title: 'Linked In' },
      { title: 'Git Hub' },
      { title: 'email' },
    ]
  }),
}

</script>

