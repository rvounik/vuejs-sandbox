<template>
    <main>
        <TheHeader />
        <section class="main_style">
            <header>My current collection</header>
            (data comes from jsonplaceholder.com)
            <ul>
                <li v-for="item in items" class="list-item">
                    {{ item.name }}
                </li>
            </ul>
        </section>
    </main>
</template>

<script>
    import TheHeader from '../../components/TheHeader/TheHeader.vue';

    export default {
        name: 'ListPage',
        components: {
            TheHeader
        },
        data() {
            return {
                items: []
            }
        },
        created() {
            this.fetch(); // comparable to React lifecycle componentDidMount
        },
        methods: {
            async fetch () {
                await fetch('https://jsonplaceholder.typicode.com/users')
                    .then(response => response.json())
                    .then(json => {
                        this.items = json
                    })
            },
        }
    }
</script>

<style>
    .list-item {
        background: black;
        color: white;
        padding: .25rem;
        width: 100px;
        height: 100px;
        border-radius: 5px;
        float: left;
        list-style-type: none;
        margin: .5rem;
    }
</style>
