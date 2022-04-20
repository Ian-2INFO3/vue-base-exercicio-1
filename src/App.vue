<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Rodape from "@/components/RodaPe.vue";
import Conteudo from "@/components/ConteNt.vue";
import Cabecalho from "@/components/CabeCalho.vue";
import Bloco from "@/components/Bloco.vue";
export default {
  components: { MenuLateral, Rodape, Conteudo, Cabecalho, Bloco },
};
</script>
<template>
  <MenuLateral />
  <Cabecalho />
  <Rodape />
  <Bloco />
  <Conteudo />
</template>
<style></style>
