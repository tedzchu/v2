<script lang="ts">
  import Icon from "./components/Icon.svelte";
</script>

<main>
  <h1>Teddy Chu</h1>
  <p>
    Yo! 👋 I'm <strong>Teddy</strong>, a Los Angeles-based
    <strong>software engineer</strong>. I sometimes respond to
    <strong>Door</strong>, as it's the funnier (and probably not real) nickname
    for my full name, Theodore.
  </p>
  <p>
    I'm currently a <strong>full stack</strong> engineer at
    <strong><a href="https://www.atlassian.com/">Atlassian</a></strong>
    building solutions to reduce friction for products trying to adopt their
    <strong><a href="https://www.atlassian.com/platform">platform</a></strong> capabilities.
  </p>
  <p>
    I have industry experience with <strong>Java</strong>,
    <strong>Python</strong>, and <strong>Kotlin</strong> on the backend and
    <strong>React</strong>
    with <strong>TypeScript</strong> on the frontend.
  </p>
  <p>
    Some hobby hats I wear include being a <strong>cook</strong> and
    <strong>foodie</strong>, <strong>weightlifter</strong>, and world-class
    <strong>video game speedrunner</strong>.
  </p>
  <p>
    If you're interested in learning more about me, you can check me out below:
  </p>
  <Icon name="github" url="https://github.com/tedzchu/" />
  <Icon name="linkedin" url="https://www.linkedin.com/in/teddy-chu/" />
  <Icon name="twitter" url="https://twitter.com/doorDoes" />
  <Icon
    name="youtube"
    url="https://www.youtube.com/channel/UCoq7axWlzAOqNnCSecnOXRA"
  />
  <br />
  <small>
    (My Twitter and YouTube are more gaming-oriented, and mostly inactive)
  </small>
  <br />
  <br />
  <p>
    Looking for more? Here's my <strong
      ><a href="/docs/TeddyChu_Resume_10_2021.pdf">resume</a></strong
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
