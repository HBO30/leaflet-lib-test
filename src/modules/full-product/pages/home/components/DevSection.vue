<template>
  <section id="dev">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col sm="4" class="hidden-xs-only">
              <v-img src="./../assets/img/ill2.svg" class="d-block ml-auto mr-auto" max-width="350px" />
            </v-col>
            <v-col cols="12" sm="8" class="white--text text-left">
              <h1 class="font-weight-light display-2 mb-2">app dev env</h1>
              <h1 class="font-weight-light">
                by Jira which is a proprietary issue tracking product developed, 
                and source version control like github I managing workflow and project development environment <br>
                To keep the project clean, Readable source code and easy to understand for others 
              </h1>
              <v-btn rounded outlined href="https://github.com/HBO30/leaflet-lib-test" target="_blank" large color="white" class="mt-4">
                <v-icon class="mr-2">
                  mdi-github
                </v-icon>
                Git Hub
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<style scoped>
#dev {
  background-image: url("./../assets/img/bgDownload.jpg");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 500px;
}

#dev .container,
#dev .row {
  height: 100%;
}
</style>