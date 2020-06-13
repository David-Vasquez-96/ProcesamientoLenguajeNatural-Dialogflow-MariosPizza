<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="6" lg="6" md="12" xs="12" sm="12">
        <v-img
          src="http://deejoe.etrumeus.com/update/images/pizza-1502140004.svg"
          class="my-1"
          contain
          height="200"
        />
        <h1 class="display-2 font-weight-bold mb-3">
          Bienvenidos a Mario's Pizza
        </h1>
        <p class="subheading font-weight-regular">
          Puedes comunicarte con nosotros y
          <br>realizar tu orden mediante nuestro asistente virtual
          <br>o desde nuestra página de <a href="https://www.facebook.com/Marios-Pizza-106498847754240/?view_public_for=106498847754240" target="_blank">Facebook</a>
        </p>
      </v-col>

      <v-col cols="6" lg="6" md="12" xs="12" sm="12">
        <div style="text-align: center;">
            <iframe class="borderAV" width="350" height="530" allow="microphone;" src="https://console.dialogflow.com/api-client/demo/embedded/b96f1195-0163-46aa-8561-211cb3ee9f06"></iframe>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({

    }),
  }
</script>

<style>
  .borderAV {
    border-color: black;
  }
</style>