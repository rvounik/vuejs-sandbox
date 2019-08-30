<template>
    <main>
        <Header />
        <section class="main_style">
            <header>List</header>
            <p>
                List goes here
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
