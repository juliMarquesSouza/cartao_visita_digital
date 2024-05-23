<template>
    <div class="containerImg">
    <img src="../../assets/icons/img-perfil.jpeg" />
    </div>
</template>

<script>
export default {
    name: "PerfilUser"
}
</script>

<style scoped>
.containerImg {
    border-radius: 50%;
    display: flex;
    justify-content: center;
    width: 6.25rem;
    height: 6.25rem;
    overflow: hidden;
}
.containerImg img {
    object-fit: cover;
    width: 100%;
    height: 100%;
}
</style>
