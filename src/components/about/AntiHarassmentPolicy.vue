<template>
    <v-container class="pa-0 my-0">
        <v-layout wrap align-start justify-start row fill-height class="my-0" >
     
            <v-flex xs12 md8 lg8 class="pa-2 my-0">
                <p class="google-font" style="font-size:180%;color:#0277bd">Política Anti-Assédio</p>
                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">Por que temos uma política oficial de anti-assédio para eventos do {{chapterDetails.ChapterName}}?</b>
                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Ele define expectativas de comportamento no evento. Basta ter uma política anti-assédio que possa impedir o assédio.</li>
                        <li class="google-font">Encoraja as pessoas a comparecer que tiveram experiências ruins em outros eventos.</li>
                        <li class="google-font">Dá instruções aos funcionários / voluntários do evento sobre como lidar com o assédio rapidamente, com o mínimo de interrupção para o evento.</li>
                    </ul>
                </p>

                <p class="google-font" style="font-size:110%">
                    <b style="font-size:120%;color: #2E2E2E;">{{chapterDetails.ChapterName}} dedica-se a proporcionar uma experiência de evento sem assédio para todos, independentemente de:</b>

                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Gênero</li>
                        <li class="google-font">orientação sexual</li>
                        <li class="google-font">Deficiência</li>
                        <li class="google-font">Ideologia de gẽnero</li>
                        <li class="google-font">Idade</li>
                        <li class="google-font">Raça</li>
                        <li class="google-font">Religião</li>
                        <li class="google-font">Nacionalidade</li>
                    </ul>

                    <span class="google-font" style="font-size:110%">O acima não é uma lista exaustiva - não toleramos o assédio de participantes do evento em qualquer forma.</span>
                </p>

                <p class="google-font" style="font-size:120%">Linguagem e imagens sexuais não são apropriadas para nenhum local do evento, incluindo palestras. Os participantes do evento que violarem essas regras podem ser expulsos do evento e o evento banido de eventos futuros, a critério dos organizadores / gerenciamento do evento.</p>

                <p class="google-font" style="font-size:110%">Assédio inclui (mas não está limitado a):
                    <ul class="mt-2" style="font-size:110%">
                        <li class="google-font">Comentários verbais ofensivos relacionados a gênero, orientação sexual, deficiência, identidade de gênero, idade, raça, religião</li>
                        <li class="google-font">O uso ou exibição de imagens sexuais em espaços públicos</li>
                        <li class="google-font">Intimidação deliberada</li>
                        <li class="google-font">Perseguição</li>
                        <li class="google-font">Assediar fotografia ou gravação</li>
                        <li class="google-font">Ruptura sustentada de conversas ou outros eventos</li>
                        <li class="google-font">Contato físico inadequado</li>
                        <li class="google-font">Atenção sexual indesejada</li>
                    </ul>
                </p>

                <p class="google-font" style="font-size:120%">Os participantes solicitados a impedir qualquer comportamento de assédio devem cumprir imediatamente. 
                    <br><br>
                    Os parceiros e convidados expositores também estão sujeitos à política anti-assédio. Em particular, expositores e oradores não devem usar imagens sexualizadas, atividades ou outro material, ou criar um ambiente sexualizado em seus decks de slides, exibir material, expor funcionários, itens promocionais ou material de demonstração.
                    <br><br>
                    Se você estiver sendo assediado, observa que outra pessoa está sendo assediada ou tenha outras dúvidas, entre em contato com um organizador ou voluntário do evento imediatamente. Organizadores e voluntários de eventos podem ser identificados por camisetas ou crachás / colhedores especiais. Os organizadores investigarão o problema e tomarão as medidas apropriadas. Isso pode incluir ajudar os participantes a entrar em contato com a segurança do local ou com a polícia local, providenciar acompanhantes ou, de outra forma, ajudar essas vítimas de assedio a se sentirem seguros pela duração do evento.
                    <br><br>
                    Embora esperemos que nunca tenhamos que invocar essa política, acreditamos que ter esse documento ajuda todos a pensar um pouco mais sobre como suas ações e palavras afetam toda a comunidade, bem como os indivíduos da comunidade.
                </p>
            </v-flex> 
           
            <v-flex xs12 md4 lg4 class="pa-2 hidden-sm-and-down">
                
            </v-flex>
        </v-layout>

    </v-container>
</template>

<script>
import ChapterDetails from '@/assets/data/chapterDetails.json'
export default {
    data() {
        return {
            chapterDetails: ChapterDetails,
        }
    },
}
</script>
