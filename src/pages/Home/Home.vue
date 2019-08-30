<template>
    <main>
        <Header />
        <section class="main_style">
            <header>Welcome!</header>
            <p>
                Welcome to the retro console preservation library. Would you like to learn more <a href="/about">About the project</a> or jump straight <a href="/list">to the overview</a>?
            </p>
        </section>
    </main>
</template>

<script>
    import Header from './../../components/Header/Header.vue';

    export default {
        name: 'Home',
        components: {
            Header
        }
    }
</script>
