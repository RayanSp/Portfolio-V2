<section class="info-article">
  <article>
    <div class="info-text">
      <h1>Hi, I am Rayan</h1>
      <h2>Frontend Developer</h2>
      <p>
        I am Rayan, a 19 year old frontend developer. As a frontend developer, I
        aspire to create visually appealing and user-friendly interfaces by
        utilizing the skills I've acquired during my studies.
      </p>
      <div class="info-links">
      <a class="contact-btn" href="/info" alt="contact button">Contact me </a>
      <a
        aria-label="this is a link to my github"
        alt="my linkedin"
        href="https://www.linkedin.com/in/rayan-spall-5b341b29a/"
        ><svg
          class="svg-linkedin"
          xmlns="http://www.w3.org/2000/svg"
          width="44"
          height="44"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="white"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" fill="none" />
          <path
            d="M4 4m0 2a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-12a2 2 0 0 1 -2 -2z"
          /> <path d="M8 11l0 5" /> <path d="M8 8l0 .01" />
          <path d="M12 16l0 -5" /> <path d="M16 16v-3a2 2 0 0 0 -4 0" />
        </svg></a
      >
      <a
        aria-label="this is a link to my github"
        alt="my github"
        href="github.com/RayanSp"
      >
        <svg
          class="svg-github"
          xmlns="http://www.w3.org/2000/svg"
          width="44"
          height="44"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="white"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" fill="none" />
          <path
            d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5"
          />
        </svg>
      </a>
    </div>
    </div>
    <div class="info-image">
      <img src="images/memeoji.png" alt="rayan logo" />
    </div>
  </article>
</section>

<style>
  .info-article {
    display: flex;
    justify-content: center;
    margin-top: 7.5rem;
  }

  article {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    background: linear-gradient(#0c0c0c, #3e3e3e);
    width: 60rem;
    height: 32.5rem;
    border-radius: 15px;
    color: white;
    margin: 1rem;
    padding: 2rem;
  }

  img {
    width: 13rem;
    height: auto;
  }

  .info-text {
    width: 40rem;
  }

  h1 {
    font-size: 4rem;
  }

  h2 {
    font-size: 2rem;
  }

  div p {
    width: 25rem;
    padding-top: 2rem;
    padding-bottom: 2rem;
  }

  .info-links {
    display: flex;
  }

  .contact-btn {
    display: flex;
    text-decoration: none;
    border: 1px solid rgb(20, 20, 20);
    background-color: rgb(20, 20, 20);
    color: white;
    padding: 0.75rem;
    border-radius: 15px;
    justify-content: center;
    transition: .2s;
    font-weight: bold;
  }

  .contact-btn:hover {
    color: rgb(20, 20, 20);
    background-color: white;
    border: 1px solid white;
  }
</style>
