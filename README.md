 <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        background-color: black;
        color: #3c3c3b;
      }
      .header-container {
        width: 100%;
        padding: 1rem;
        display: flex;
        flex-direction: column;
        gap: 1rem;
      }
      .header-container > h1 {
        color: #3c3c3b;
        text-align: center;
      }
      .header-container > hr {
        border: 1px solid #3c3c3b;
      }
      .front-image {
        width: 100%;
      }
      .header-links {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        gap: 1rem;
      }
      .header-links > a {
        display: flex;
        flex-direction: row;
        align-items: center;
        gap: 0.3rem;
        padding: 0.3rem;
        border-radius: 0.4rem;
        border: 2px solid #3c3c3b;
        font-weight: 900;
        color: #808080;
        text-decoration: none;
      }
      .main-container {
        padding: 1rem;
        display: flex;
        flex-direction: column;
        gap: 1rem;
      }
      .container {
        display: flex;
        flex-direction: column;
      }
      pre {
        font-size: 1rem;
        border: 2px solid grey;
        border-radius: 5px;
        padding: 14px;
        display: flex;
        background-image: repeating-linear-gradient(
          180deg,
          #fff 24px,
          #fff 48px
        );
      }
    </style>

 <header class="header-container">
      <h1>Hi!</h1>
      <img src="https://raw.githubusercontent.com/jom3/jom3/main/images/front-image.jpg" alt="" class="front-image" />
      <div class="header-links">
        <a href="https://twitter.com/joams_mg" target="_blank"
          ><img src="https://raw.githubusercontent.com/jom3/jom3/main/images/social/x.svg" alt="" />TWITTER</a
        >
        <a href="https://discord.com/users/520993331975553035" target="_blank"
          ><img src="https://raw.githubusercontent.com/jom3/jom3/main/images/social/discord.svg" alt="" />DISCORD</a
        >
        <a
          href="https://www.linkedin.com/in/joams-mogro-gomez-442691103/"
          target="_blank"
          ><img src="https://raw.githubusercontent.com/jom3/jom3/main/images/social/linkedin.svg" alt="" />LINKEDIN</a
        >
        <a href="mailto:joamsmg@gmail.com" target="_blank"
          ><img src="https://raw.githubusercontent.com/jom3/jom3/main/images/social/gmail.svg" alt="" />TWITTER</a
        >
      </div>
    </header>
    <main class="main-container">
      <div class="container">
        <h1>About me</h1>
        <pre>
          {
            name: 'Joams',
            last_name: 'Mogro Gomez',
            age: 29,
            passions: ['Web developer','Frontend developer','Backend developer'],
            current_occupation: 'Freelance'
          }
        </pre>
      </div>
      <div class="container">
        <h1>Skills</h1>
        <pre>
          {
            languages: ['JavaScript','TypeScript'],
            frontend: ['Angular','React','Astro'],
            backend: ['Nodejs','Nestjs'],
            databases: ['PostgreSQL','Mongodb']
          }
        </pre>
      </div>
    </main>

