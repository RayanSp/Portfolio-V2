<script>

</script>

<header> 
    <a href="/" class="header-logo">
        <img src="images/logoklowed.png" alt="rayan logo" />
    </a>
    <div class="header-navigation">
        <a href="/" class="left">
            <a href="/"><img src="images/huisjemeteffects.png" class="nav-icons" alt="homepage"></a>
        </a>
        <a href="/info" class="right">
            <a href="/info"><img src="images/infometeffects.png" class="nav-icons" alt="info page"></a>
        </a>
    </div>
    <div class="header-socials">
        <a href="https://github.com/RayanSp">GitHub<img src="images/arrow.png" class="arrow-img" alt="arrow logo"></a>
        <a href="https://www.linkedin.com/in/rayan-spall-5b341b29a/">Linkedin<img src="images/arrow.png" class="arrow-img" alt="arrow logo"></a>
    </div>
</header>



<style>

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 1rem;
    /* width: 100%; */
}

.header-logo {
    display: flex;
    flex-direction: row;
}

.nav-icons {
    height: 2rem;
}

img {
    height: 3rem;
}

/* p {
    color: white;
    transform: translateY(80%);
} */

a {
    text-decoration: none;
}

.header-navigation {
    display: flex;
    flex-direction: row;
}

.header-navigation .left {
    display: flex;
    flex-direction: row;
    background-color: #363636;
    border-top-left-radius: 12px;
    border-bottom-left-radius: 12px;
    width: 5rem;
    height: 3rem;
    justify-content: center;
}

.header-navigation .right {
    display: flex;
    flex-direction: row;
    background-color: #363636;
    border-top-right-radius: 12px;
    border-bottom-right-radius: 12px;
    width: 5rem;
    height: 3rem;
    justify-content: center;
}

.left {
    transition: .2s ease-in-out
}

.right {
    transition: .2s ease-in-out
}

.left a {
    margin: auto;
}

.right a {
    margin: auto;
}

.right:hover {
    background-color: #282828;
}


.left:hover {
    background-color: #282828;
}

div a {
    text-decoration: none;
    color: white;
}

.header-socials {
    display: flex;
}

.header-socials a {
    margin: auto;
    padding-right: 1rem;
    transition: 2s;
}

.header-socials a:hover {
    text-decoration: 2px underline;
}

.arrow-img {
    height: 1.5rem;
    margin: auto;
}

</style>