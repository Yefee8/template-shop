<template>
  <div>
    <Head>
      <title>template shop! - buy some new templates!</title>
      <meta name="description" content="buy some templates from template shop!">
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    </Head>
    <Header />

    <Main />

    <Packs class="mt-4 md:mt-8"/>

    <Footer class="mt-4 md:mt-8"/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=M+PLUS+1:wght@400;500&family=Nothing+You+Could+Do&display=swap');

body {
  font-family: 'M PLUS 1';
}
</style>
