<template>
  <v-content class="pa-0">

    <v-container fluid class="mt-3 mb-0">
      <v-layout wrap align-center justify-center row fill-height class="my-0">
        <v-flex xs12 md10 class="my-0">
            <p class="google-font mb-0" style="font-size:200%;color:#616161">Equipe</p>
            <p class="google-font mt-0 mb-0" style="font-size:110%">O Google é conhecido em todo o mundo. Todos estão "pesquisando", verificando "mapas" e se comunicando no "Gmail". Para usuários simples, eles são serviços que simplesmente funcionam, mas não para nós. Os desenvolvedores veem muito mais: APIs, problemas de escalabilidade, pilhas complexas de tecnologia. E é disso que trata o GDG.</p>

             <p class="google-font mt-3 mb-0" style="font-size:110%">Nosso objetivo é organizar espaços para conectar especialistas das mais diversas tecnologias com o público alencarino para impulsionar o desenvolvimento de TI da região. Nossa equipe principal é:</p>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <coreTeam/>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10 class="">
          <organizingTeam/>
        </v-flex>
      </v-layout>
    </v-container>

   


  </v-content>
  
</template>

<script>
import TeamDetails from '@/assets/data/chapterDetails.json'
import coreTeam from '@/components/team/coreTeam'
import organizingTeam from '@/components/team/organizingTeam'
  export default {
    components: {
      coreTeam,
      organizingTeam
    },
    data() {
      return {
        TeamDetails: TeamDetails,
      }
    },
  }
</script>
