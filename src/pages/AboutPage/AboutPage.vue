<template>
    <main>
        <TheHeader />
        <section class="main_style">
            <header>About this project</header>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque enim neque, interdum non purus nec, bibendum sagittis tellus. Suspendisse pulvinar consequat mollis. Aliquam egestas laoreet ipsum, nec sodales justo commodo sed. Pellentesque ut libero sem. Donec in est sed nisl faucibus rutrum semper id risus. Nam gravida id ipsum quis suscipit. Vestibulum ut dictum lectus, in vehicula nulla.
            </p>
        </section>
    </main>
</template>

<script>
    import TheHeader from '../../components/TheHeader/TheHeader.vue';

    export default {
        name: 'Home',
        components: {
            TheHeader
        }
    }
</script>
