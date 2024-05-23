<template>
    <div class="bio">
        <section>
        <h1 class="user">Juliana Marques</h1>
        <p class="font-600, Green">Amazonas, Brasil</p></section>
        <p>"Front-end developer and avid reader"</p>     
    </div>
</template>

<script>
import Social from './Social.vue'
export default {
  components: { Social },
    name: "BioUser"
}
</script>

<style scoped>
.bio {
    padding: 0.625;
    gap: 1rem;
    display: grid;
}
.bio section {
    display: grid;
    gap: 0.3rem;
}
.user {
    font-size: 1.2rem;
    text-align: center;
    font-weight: 700;
}
   h1{
    color: hsl(0, 0%, 100%)

   }

.Green {
   color: hsl(75, 94%, 57%);
   text-align: center;   
}
    p{
        color: hsl(0, 0%, 100%);
        text-align: center;
        font-size: 0.813rem;
        font-weight: 300;
    }


</style>