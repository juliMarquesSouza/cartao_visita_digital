<template>
  <a :href="link" target="_blank" class="btn-social">{{ title }}</a>
</template>

<script>
export default {
    name: "Social",
    props: {
    title: {
        type: String,
        required: true,
    },
    link: {
        type: String,
        required: true,
    }
    }
}
</script>

<style scoped>
    .btn-social {
        widows: 100%;
        background-color: hsl(0, 0%, 20%);
        color: #fff;
        border-radius: 0.313rem;
        padding: 0.625rem 1.25rem;
        display: inline-block;
        width: 100%;
        text-align: center;
        text-decoration: none;
        cursor: pointer;
        font-size: 0.7rem;
    
    }
    .btn-social:hover {
        background-color: hsl(75, 94%, 57%);
        transition: background-color 0.3s;

    }

</style>