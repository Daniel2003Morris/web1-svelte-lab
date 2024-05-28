<script>
    let navItems = [
        { text: "Quiz", href: "/Games/Quizes"},
		{ text: "Other", href: "/other"}
    ];
</script>

<style>
    .sidebar {
        position: fixed;
        top: 0;
        left: 0;
        width: 200px;
        height: 100vh;
        background-color: whitesmoke;
        padding: 1em;
    }
    .nav-item {
        cursor: pointer;
        padding: 0.5em;
        border-bottom: 1px solid black;
    }
    .nav-item:hover {
        background-color: #e4e4e4;
    }
    .nav-link {
        display: block;
        padding: 0.5em 1em;
        text-decoration: none;
        color: black;
    }
    .nav-link:hover {
        background-color: #ddd;
    }
</style>

<div class="sidebar">
    {#each navItems as item}
        <div class="nav-item">
            <a class="nav-link" href="{item.href}">{item.text}</a>
        </div>
    {/each}
</div>