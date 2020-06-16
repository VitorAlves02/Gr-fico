<template>
    <div class="graficos">
      <h2>Exemplos de gráficos de vários tipos feitos usando a lib ApexCharts.js</h2>
      <br />
      <br />
      <br />
      <grafico-area />
      <br />
      <br />
      <grafico-linha />
      <br />
      <br />
      <grafico-coluna />
      <br />
      <br />
      <grafico-barra />
      <br />
      <br />
      <grafico-linha-tempo />
      <br />
      <br />
      <grafico-pizza />
      <br />
      <br />
      <grafico-radar />
      <br />
      <br />
    </div>
</template>

<script>
import GraficoArea from "../components/graficos/Area.vue";
import GraficoLinha from "../components/graficos/Linha.vue";
import GraficoColuna from "../components/graficos/Coluna.vue";
import GraficoBarra from "../components/graficos/Barra.vue";
import GraficoLinhaTempo from "../components/graficos/LinhaTempo.vue";
import GraficoPizza from "../components/graficos/Pizza.vue";
import GraficoRadar from "../components/graficos/Radar.vue";

export default {
  components: {
    "grafico-area": GraficoArea,
    "grafico-linha": GraficoLinha,
    "grafico-coluna": GraficoColuna,
    "grafico-barra": GraficoBarra,
    "grafico-linha-tempo": GraficoLinhaTempo,
    "grafico-pizza": GraficoPizza,
    "grafico-radar": GraficoRadar
  }
};
</script>

<style scoped>
.graficos {
  width: 80%;
  margin: 0px auto;
  padding: 50px 0px;
  text-align: center;
}
</style>
