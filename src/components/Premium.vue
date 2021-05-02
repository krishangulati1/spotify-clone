<template>
  <PremHome
  color="#a0c3d2"
  title="Introducing Premium for the whole family"
  subtitle='Family members can now enjoy up to 6 Premium accounts.'
  subtitle_two='Just for ₹199'
  btn='get premium family'
  btn_two='see other plans'
  :show='bone'
   />
   <ConnetMusic/>
   <Pricing />
</template>

<script>
import PremHome from "./PremHome";
import Pricing from "./Pricing";
import ConnetMusic from "./ConnetMusic";
export default {
  name: "Premium",
  components: {
    PremHome,
    Pricing,
    ConnetMusic
  }

}
</script>
