<template>
  <div class="containerPrincipal">
  <main class="menu">
    

    <div class="info"> 
    <PerfilUser />
    <BioUser />
    </div>

    <div class="redesSociais">
      <Social title="GitHub" link="https://github.com/juliMarquesSouza"></Social>
        <Social title="Frontend Mentor" link="https://www.frontendmentor.io/"></Social>
        <Social title="LinkedIn" link="https://www.linkedin.com/in/juliana-marques-9ab335294/"></Social>
        <Social title="Twitter" link="https://x.com/?lang=pt-br"></Social>
        <Social title="Instagram" link="https://www.instagram.com/j_marquexx/"></Social>
    </div>
  </main>
</div>
</template>

<script setup>
import TemplateIndex from "@/components/template/TemplateIndex.vue";
import PerfilUser from "@/components/atomos/PerfilUser.vue";
import BioUser from "@/components/moleculas/BioUser.vue";
import Social from "@/components/moleculas/Social.vue";
</script>

<style scoped>
.containerPrincipal{
  background: hsl(0, 0%, 8%);
  width: 100vw;
  height: 100vh;
  display: flex;
  align-items: center;
}

.menu {
  background: hsl(0, 0%, 12%);
  width: 18.75rem;
  height: auto;
  margin: auto;
  padding: 1.25rem;
  justify-content: center;
  align-items: center;
  border-radius: 0.625rem;
}

.info {
  display: grid;
  place-items: center;
}

.redesSociais {
  display: flex;
  flex-direction: column;
  gap: 0.625rem;
  margin-top: 0.6rem;
}



</style>
