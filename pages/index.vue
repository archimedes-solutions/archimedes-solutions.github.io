<template>
  <div>
    <Hero/>
    <Services/>
    <Portfolio/>
    <Team/>
    <Feedback/>
    <Contacts/>
  </div>
</template>

<script>
import Services from "../components/index/Services";
import Hero from "../components/index/Hero";
import Portfolio from "../components/index/Portfolio";
import Team from "../components/index/Team";
import Feedback from "../components/index/Feedback";
import Contacts from "../components/index/Contacts";

export default {
  components: {
    Contacts,
    Feedback,
    Team,
    Portfolio,
    Hero,
    Services,
  }
}
</script>
