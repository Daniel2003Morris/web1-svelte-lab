<script>
    import Picture from "./Picture.svelte";
    import Details from "./Details.svelte";
    import Footer from "./Footer.svelte";
</script>

<section>
    <Picture />
    <Details />
    <Footer />
</section>

<style>
    section{
        display: flex;
        border: 1px solid black;
        padding: 10px;
    }
</style>