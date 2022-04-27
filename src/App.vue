<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Rodape from "@/components/RodaPe.vue";
import Conteudo from "@/components/MenuConteudo.vue";
import Cabecalho from "@/components/CabeCalho.vue";
export default {
  components: { MenuLateral, Rodape, Conteudo, Cabecalho },
};
</script>
<template>
  <MenuLateral />
  <Cabecalho />
  <Rodape />
  <Conteudo />
</template>
<style></style>
