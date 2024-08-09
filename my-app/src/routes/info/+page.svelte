<script> 

    import Header from "$lib/components/Header.svelte";
    import Info from "$lib/components/Info.svelte";

</script>

<Header />

<section>
    <article class="safari-article">
        <a href="https://github.com/RayanSp"><img src="images/rayansp.png" class="github-img" alt="rayan logo" /></a>
    </article>
    <article class="projects-article">
        <h1>1. Toolgankelijkheid</h1>
        <p class="project-desc">Vervoerregio Amsterdam '24 - Een tool voor Vervoerregio Amsterdam waarmee medewerkers intern hun partners kunnen controleren op de toegankelijkheid van hun websites.</p>
        <div class="img-div">
            <img class="projects-image" src="images/vervoerregio.png" alt ="foto website vervoerregio amsterdam">
        </div>
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

    .github-img {
        width: 50rem;
        height: auto;
        transition: .3s ease-in-out;
    }

    .github-img:hover {
        width: 52rem;
        cursor: pointer;
    }

    .projects-article {
        display: flex;
        flex-direction: column;
        align-self: center;
        background: linear-gradient(#3e3e3e, #0c0c0c);
        width: 45rem;
        height: 32.5rem;
        border-radius: 15px;
        color: white;
        margin: 1rem;
        padding: 2rem;
    }

    h1 {
        font-size: 2rem;
    }

    .project-desc {
        margin-bottom: 2rem;
    }
     

    .img-div {
        display: flex;
        justify-content: center;
    }

    .projects-image {
        filter: blur(2px);
        width: 40rem;
        border-radius: 15px;
    }

</style>