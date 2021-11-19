<template>
    <section class="banner text-center position-relative">
        <div class="caption position-absolute top-50 start-50 translate-middle">
        <p>Lorem ipsum dolor sit.</p>
        <h2>CREATITIVE HAVE NEW LEVEL</h2>
        <a class="btn carrer">Preview</a>
        <a class="btn carrer">Get Themes</a>
        </div>
    </section>
</template>
<style scoped>
    .banner{
        background-image: url(../assets/img/header.jpg);
        background-position: center;
        background-size: cover;
        height: 85vh;
        width: 100%;
        background-color: var(--second-color);
        background-blend-mode: multiply;
        color: var(--white);
    }
    .banner .caption .carrer{
        color: var(--white);
        border: 2px solid var(--white);
        padding: 1% 10%;
        background-color: transparent;
        margin: 10px;
        transition: .7s ease-in-out;
    }
    .banner .caption .carrer:hover{
        background-color: var(--main-color);
    }

</style>
<script>
export default {
    name : 'HomeComp'
}
</script>