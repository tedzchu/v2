<script lang="ts">
  import Icon from "./components/Icon.svelte";
</script>

<main>
  <h1>Teddy Chu</h1>
  <p>
    Yo! 👋 I'm <strong>Teddy</strong>, a Los Angeles-based
    <strong>software engineer</strong>. I sometimes respond to
    <strong>Door</strong> 🚪, as it's the funnier "nickname" for my full name, Theodore.
  </p>
  <p>
    I'm currently a <strong>full stack</strong> engineer at
    <strong><a href="https://www.atlassian.com/">Atlassian</a></strong>
    building solutions to reduce friction for products trying to adopt Atlassian's
    <strong><a href="https://www.atlassian.com/platform">platform</a></strong> capabilities.
  </p>
  <p>
    I have industry experience writing <strong>Java</strong>,
    <strong>Python</strong>, and <strong>Kotlin</strong> backends and
    <strong>React</strong>
    with <strong>TypeScript</strong> frontends. If I'm lucky, I sometimes get to
    write
    <strong>Terraform</strong>.
  </p>
  <p>
    I'm a budding <strong>functional programming</strong> enthusiast, trying to
    get more experience with <strong>Haskell</strong> in my spare time.
  </p>
  <p>
    Some hobby hats I wear include being a <strong>cook</strong>,
    <strong>videographer</strong>, <strong>powerlifter</strong>, and world-class
    <strong>video game speedrunner</strong>.
  </p>
  <p>
    If you're interested in learning more about me, you can check me out here:
  </p>
  <Icon name="github" url="https://github.com/tedzchu/" />
  <Icon name="linkedin" url="https://www.linkedin.com/in/teddy-chu/" />
  <br />
  <br />
  <p>
    Looking for more? Here's my <strong
      ><a href="/docs/TeddyChu_Resume_02_2022.pdf">resume</a></strong
    >, which has my email if you're looking to get in touch. Cheers!
  </p>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 350px;
    margin: 0 auto;
  }

  h1 {
    color: #00c6ff;
    text-transform: uppercase;
    font-size: 3em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }

    h1 {
      font-size: 4em;
    }
  }
</style>
