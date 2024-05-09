<script>
    import Header from '../components/Header.svelte';
    import Card from '../components/Card.svelte';
</script>
<Header />
<section>
    <Card />
    <Card />
</section>

<style>
    section{
        display: flex;
        justify-content: space-around;
    }
</style>
