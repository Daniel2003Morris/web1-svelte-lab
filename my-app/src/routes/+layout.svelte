<script>
    import Header from '../components/Header.svelte';
    import Footer from '../components/Footer.svelte';
    import Sidebar from '../components/Sidebar.svelte';
    let navitems = [
        { text: "home", href: "/" },
        { text: "profile image", href: "/profile/" }
    ]
</script>

<div class="container">
    <header><Header /></header>
    <div class="left-side"><Sidebar /></div>
    <slot />
    <Footer />
</div>