<script>
    import Sidebar from "../../components/Sidebar.svelte"
    let navitems = [
        { text: "home", href: "/" },
        { text: "profile image", href: "/profile/profile-image"},
        { text: "company details", href: "/profile/company"},
        { text: "Contact details", href: "/profile/contact-details"}
    ]
</script>
<div class="left-side"><Sidebar {navitems} /></div>
<slot />