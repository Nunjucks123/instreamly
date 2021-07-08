<template>
  <Header></Header>
  <Admission></Admission>
  <Format></Format>
  <Streamerzy></Streamerzy>
  <Prizes></Prizes>
  <Contact></Contact>
  <Jury></Jury>
  <Deadlines></Deadlines>
  <Participation></Participation>
  <QandA></QandA>
  <Usefulllinks></Usefulllinks>
  <Footer></Footer>
</template>

<script>
import Header from "./components/Header.vue";
import Admission from "./components/Admission.vue";
import Format from "./components/Format.vue";
import Streamerzy from "./components/Streamerzy.vue";
import Prizes from "./components/Prizes.vue";
import Contact from "./components/Contact.vue";
import Jury from "./components/Jury.vue";
import Deadlines from "./components/Deadlines.vue";
import Participation from "./components/Participation.vue";
import QandA from "./components/QandA.vue";
import Usefulllinks from "./components/Usefull-links.vue";
import Footer from "./components/Footer.vue";
export default {
  components: {
    Header,
    Admission,
    Format,
    Streamerzy,
    Prizes,
    Contact,
    Jury,
    Deadlines,
    Participation,
    QandA,
    Usefulllinks,
    Footer,
  },
};
</script>