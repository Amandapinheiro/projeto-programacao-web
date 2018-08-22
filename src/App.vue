<template>
  <div id="app">
    <img :src="linkDaImagem" :alt="titulo">
    <h1>{{ msg }}</h1>
    <h2>{{ outramensagem }}</h2>
    <h2>Amanda é daora!</h2>
    
  </div>
</template>

<script>
  export default {
    name: 'app',
    data () {
      return {
        msg: 'Amanda é legal!',
        outramensagem: 'E ela estuda no IFRN!',
        linkDaImagem: 'https://conteudo.imguol.com.br/c/bol/fotos/09/2016/03/03/3mar2016---um-filhote-de-cachorro-da-raca-golden-retriver-precisou-usar-aparelho-para-corrigir-os-dentes-wesley-de-seis-meses-estava-com-dificuldade-para-mastigar-1457031861450_642x700.jpg',
        titulo: 'Um cachorrinho'
      }
    }
  }
</script>

<style>

</style>
