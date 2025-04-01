<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Regímenes

    .row.mb-5
      .col-lg-2.order-2
        figure
          img(src="@/assets/curso/tema2/1.svg", data-aos="zoom-in")
      .col-lg-10.order-1.mb-3.mb-lg-0
        p Los regímenes tributarios establecen las normas y clasificaciones que rigen la obligación de contribuir al sostenimiento del Estado. Su estructura permite diferenciar a los contribuyentes según su actividad económica, ingresos y responsabilidades fiscales. Comprender estos regímenes es esencial para el cumplimiento de la normativa y la correcta aplicación de los impuestos.

    separador

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 De acuerdo con normativa

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/2.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        div.bg-color-9.tarjeta.p-4.mb-5(data-aos="fade-right")
          p <b>De acuerdo con el Estatuto Tributario-0624 de 1989</b>, es fundamental atender la clasificación de los contribuyentes y no contribuyentes; por ende, es importante identificar el tipo de impuesto y las responsabilidades que se tiene en cada uno de estos.

          p Para continuar con el componente formativo propuesto, es importante abordar los términos de persona natural y jurídica, teniendo en cuenta que se manejan en el desarrollo del proceso de formación; por lo tanto, los relacionamos a continuación:

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
