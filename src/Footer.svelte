<script>
</script>


<footer class="footer has-background-dark is-bold">
    <div class="content has-text-centered has-text-white-ter">
        <p class="is-size-6">
            <a href="/">Svelte Norris</a> by <a href="https://www.thebrandolorian.com" >The Brandolorian</a>
        </p>
        <p>
            Made with <a href="https://svelte.dev"> Svelte </a>, the javascript framework. Jokes are from the <a href="https://api.chucknorris.io/">Chuck Norris Jokes API</a>
        </p>
        <img class="bounce" src="https://i.imgur.com/1KdXY73.png" alt="brando is happy" width="64px"/>
    </div>
</footer>

<style>
    footer {
        height: 30%;
    }

    a {
        color: #c3c3c3;
        font-weight: bold;
    }

    a:hover {
        color: gray;
        text-decoration: none !important;
    }

    a:active {
        color: #8c1313;
        font-size: 95%;
        text-decoration: none !important;
    }

    .bounce {
        animation: brando-bounce 1s ease infinite alternate;
    }

    @keyframes brando-bounce {
        0% {
            transform: translateY(0) scale(1)
        }
        100% {
            transform: translateY(16px) scale(1.25)
        }
    }
</style>
