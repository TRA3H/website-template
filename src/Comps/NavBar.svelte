<script>
  import { each } from "svelte/internal";


    const navItems=[
        {title: "About" , url: "#About"},
        {title: "Experiences" , url: "#Experiences"},
        {title: "Projects" , url: "#Projects"},
        {title: "Cyrus", url: "#Cyrus"}
    ]
</script>

<nav>
    <section class="container_nav" id="/">
        {#each navItems as {title,url}}
        <a href={url} class="nav_item">{title}</a>
        {/each}
    </section>
</nav>

<style>
    .container_nav{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: row;

    }

    .nav_item{
        color: white;
        font-weight: 600;
        font-size: 2rem;
        margin: 0 2rem;
        transition: 400ms all;
    }

    .nav_item:hover{
        color: #646cff;
    }
</style>