<script>
    import Svg from "../lib/svg/svg.svelte";
  </script>
  
  <main>
    <section>
      <!-- <img src="/Squad2C-Nazneen.JPG" alt="Squad2C-Nazneen" /> -->
      <Svg />
      <p>20 likes</p>
      <p>First day school picture.</p>
      <p>#Class20242025 #FDND #Github/Nazneen05x</p>
    </section>
  </main>
  
  <style>
    main {
      padding: 7em;
    }
  
    section {
      background-color: white;
      width: 25em;
      height: 34em;
      border-radius: 0.3em;
      margin: 0% auto;
    }
  
    /* img {
      width: 20em;
      height: 20em;
      padding: 2.5em;
    } */
  
    p {
      font-family: Verdana, Geneva, Tahoma, sans-serif;
      font-weight: bold;
      font-size: small;
      position: relative;
      bottom: 6em;
      margin-left: 3em;
    }
  
    p:nth-of-type(2) {
      font-weight: normal;
      bottom: 6.5em;
    }
  
    p:nth-of-type(3) {
      font-weight: normal;
      color: #166ff5;
      bottom: 7em;
    }
  </style>
  
  