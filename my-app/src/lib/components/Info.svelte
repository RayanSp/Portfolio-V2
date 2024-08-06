<script>
</script>

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
        <a class="contact-btn" href="/info" alt="contact button"
          >Contact Me<svg
            version="1.1"
            class="arrow-right"
            id="icons_1_"
            xmlns="http://www.w3.org/2000/svg"
            x="0"
            y="0"
            viewBox="0 0 128 128"
            style="enable-background:new 0 0 128 128"
            xml:space="preserve"
            ><style>
              .st0 {
                display: none;
              }
              .st1 {
                display: inline;
              }
              .st2 {
                fill: white;
              }
            </style><g id="row1_1_"
              ><g id="_x31__3_"
                ><path
                  class="st2"
                  d="M64 0C28.7 0 0 28.7 0 64s28.7 64 64 64 64-28.7 64-64S99.3 0 64 0zm0 121.6C32.2 121.6 6.4 95.8 6.4 64S32.2 6.4 64 6.4s57.6 25.8 57.6 57.6-25.8 57.6-57.6 57.6zM49.2 38.4 73.6 64 49.2 89.6h13.5L86.4 64 62.7 38.4H49.2z"
                  id="_x32__2_"
                /></g
              ></g
            ></svg
          ></a
        >
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
  <article class="form-article">
    <form>
      <h1>Contact</h1>
      <fieldset class="form-wrapper">
        <label for="name" class="form-label"><span>Name</span></label>
        <input
          type="text"
          name="name"
          id="name"
          required
          placeholder="Your name..."
          class="input-field"
        />

        <label for="email" class="form-label"><span>Email</span></label>
        <input
          type="email"
          name="email"
          id="email"
          required
          placeholder="Your email..."
          class="input-field"
        />

        <label for="message" class="form-label"><span>Message</span></label>
        <textarea
          name="message"
          id="message"
          required
          placeholder="Your message..."
          class="input-field"
        ></textarea>
      </fieldset>

      <button type="submit" class="btn btn-primary">Send</button>
    </form>
  </article>
</section>

<style>
  section {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

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
    width: 55rem;
    height: 30rem;
    border-radius: 15px;
    color: white;
    margin: 1rem;
    padding: 2rem;
  }

  img {
    width: 13rem;
    height: auto;
  }

  /* .info-text {
    width: 40rem;
  } */

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
    background-color: rgb(20, 20, 20);
    color: white;
    padding: 0.75rem;
    border-radius: 15px;
    justify-content: center;
    transition: 0.2s;
    font-weight: bold;
    font-size: 1.2rem;
  }

  #icons_1_ {
    width: 1.5rem;
    padding-left: 5px;
  }

  .contact-btn:hover {
    color: rgb(20, 20, 20);
    background-color: white;
  }

  h1 {
    color: var(--c-white);
    text-align: center;
  }

  .form-article {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    background: linear-gradient(#3e3e3e, #0c0c0c);
    width: 40rem;
    height: 30rem;
    border-radius: 15px;
    color: white;
    margin: 3rem;
    padding: 0rem;
    margin-bottom: 5rem;
  }

  /* Wrapper for Form Elements */
  .form-wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center;
    border: none;
  }

  /* Labels */
  .form-label {
    font-weight: bold;
    font-size: 14px;
    color: var(--c-white);
  }

  /* Input and Textarea Styling */
  .input-field {
    width: 20rem;
    padding: 8px 12px;
    font-size: 14px;
    border: 1px solid #ccc;
    border-radius: 4px;
    transition: border-color 0.3s ease-in-out;
    margin-bottom: 2rem;
  }

  .input-field:focus {
    border-color: 2px solid red;
    outline: none;
  }

  /* Button Styling */
  .btn {
    padding: 10px 14px;
    font-size: 14px;
    font-weight: bold;
    text-align: center;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease-in-out;
  }

  .btn-primary {
    background-color: var(--c-lightblue);
    color: #fff;
  }

  .btn-primary:hover {
    background-color: var(--c-darkblue);
  }

  input:valid {
    border: 2px solid lightgreen;
  }

  textarea:valid {
    border: 2px solid lightgreen;
  }

  form:invalid .btn-primary {
    background-color: #6c757d;
    cursor: not-allowed;
  }
</style>
