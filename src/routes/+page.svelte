<script>
    import NowPlaying from "./Components/nowPlaying.svelte";
    import "../lib/styles.css";
</script>

<div class="container">
    <div class="body">
        <h2 class="title">
            This is a test.
        </h2>
    </div>
</div>

<NowPlaying/>

<style>

    .container {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh; /* Adjust as needed */
    }
    .title {
        color: red;
        text-align: center;
    }

</style>