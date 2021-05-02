<template>
  <div class="yourmusic">

      <Music img='https://i.scdn.co/image/ab67616d00001e0252fe6875028c892308ffc2f7' title='Daily Mix 1'/>
      <Music img='https://i.scdn.co/image/ab67616d00001e02e7c61465b863bed7d6f7a2ba' title='Daily Mix 2'/>
      <Music img='https://i.scdn.co/image/ab67616d00001e02ba5db46f4b838ef6027e6f96' title='Daily Mix 3'/>
      <Music img='https://dailymix-images.scdn.co/v2/img/f8c23e3e6a1f64489869915e36b6fb358e8cff76/1/en/large' title='Daily Mix 4'/>
      <Music img='https://i.scdn.co/image/ab67616d00001e02abfecfcab2c8ebe924b2dd9f' title='Daily Mix 5'/>
      <Music img='https://i.scdn.co/image/ab67616d00001e02d7c47da4f602a212a38254ea' title='Daily Mix 6'/>

  </div>
</template>

<script>
import Music from "./Music.vue";
export default {
    name: "YourMusic",
    components: {
        Music
    }
}
</script>

<style>
    .yourmusic {
        width: 80%;
        margin: auto;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        margin-bottom: 80px;
    }
</style>