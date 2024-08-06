<script> 

    import Header from "$lib/components/Header.svelte";
    import Info from "$lib/components/Info.svelte";

</script>

<Header />

<section>
    <article class="safari-article">
        <img src="images/rayansp.png" alt="rayan logo" />
    </article>
    <article class="projects-article">

    </article>
</section>


<style>

    section {
        display: flex;
        flex-direction: column;
        margin-top: 5rem;
    }

    .safari-article {
        display: flex;
        justify-content: center;
    }

    img {
        width: 50rem;
        height: auto;
    }

    .projects-article {
        display: flex;
        align-self: center;
        background: linear-gradient(#3e3e3e, #0c0c0c);
        width: 45rem;
        height: 32.5rem;
        border-radius: 15px;
        color: white;
        margin: 1rem;
        padding: 2rem;
    }

</style>