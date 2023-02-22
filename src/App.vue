<template>
  <NavBar />
  <ContenuHomepage />
  <SectionAnniv />
  <SectionBlanc />
  <SectionInterieur />
  <SectionClub />
  <SectionAvis /> 
  <SectionFooter /> 
</template>

<script>
import NavBar from './components/NavBar.vue'
import ContenuHomepage from './components/ContenuHomepage.vue'
import SectionAnniv from './components/SectionAnniv.vue'
import SectionBlanc from './components/SectionBlanc.vue'
import SectionInterieur from './components/SectionInterieur.vue'
import SectionClub from './components/SectionClub.vue'
import SectionAvis from './components/SectionAvis.vue'
import SectionFooter from './components/SectionFooter.vue'


export default {
  name: 'App',
  components: {
    NavBar,
    ContenuHomepage,
    SectionAnniv,
    SectionBlanc,
    SectionInterieur,
    SectionClub,
    SectionAvis,
    SectionFooter,
  }
}
</script>


<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
