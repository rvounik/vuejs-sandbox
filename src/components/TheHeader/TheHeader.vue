<template>
        <header>
        <h1>Retro Console Preservation Library</h1>
        <ul class="test">
            <li>
                <a href="/">Home</a>
            </li>
            <li>
                <a href="/about">About</a>
            </li>
            <li>
                <a href="/list">List</a>
            </li>
        </ul>
    </header>
</template>

<style scoped>
    .test {
        background: black;
        height: 1rem;
        padding: .5rem;
    }

    h1 {
        padding: 1rem 1.5rem;
        color: white;
        background: #000044;
        font-family: "Gill Sans";
    }

    ul {
        list-style-type: none;
    }

    li {
        float: left;
        padding: 0 1rem;
        border-right: solid 1px white;
    }

    li:last-child {
        border: none;
    }

    li a {
        text-decoration: none;
        color: white;
        font-size: 0.75rem;
        text-transform: uppercase;
    }
</style>
