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
        width: 60rem;
        height: auto;
    }

    .projects-article {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        background: linear-gradient(#3e3e3e, #0c0c0c);
        width: 60rem;
        height: 32.5rem;
        border-radius: 15px;
        color: white;
        margin: 1rem;
        padding: 2rem;
    }

</style>