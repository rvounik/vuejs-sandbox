<template>
    <main>
        <TheHeader />
        <section class="main_style">
            <header>Welcome!</header>
            <p>
                Welcome to the retro console preservation library. Would you like to learn more <a href="/about">About the project</a> or jump straight <a href="/list">to the overview</a>?
            </p>
        </section>
    </main>
</template>

<script>
    import TheHeader from '../../components/TheHeader/TheHeader.vue';

    export default {
        name: 'HomePage',
        components: {
            TheHeader
        }
    }
</script>
