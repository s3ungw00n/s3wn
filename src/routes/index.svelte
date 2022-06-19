<svelte:head>
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css"
  />
</svelte:head>

<header class="header">
  <div class="greeting px-4">
    <div>
      {'Hello, There'}
      <div style="display: inline-block; width: 2rem">
        <img alt="wave hand" src="hello_emoji.svg" width="100%" />
      </div>
      <span class="ms-1">I'm</span>
    </div>
    <h1>SeungWoon Lee</h1>
    <div class="text-info">Fullstack Web Developer</div>
    <a href="https://blog.s3wn.com" target="_blank">Blog</a>
    <a href="https://github.com/s3ungw00n" target="_blank">Github</a>
    <a href="https://twitter.com/s3ungw00n" target="_blank">Twitter</a>
  </div>
</header>

<style>
  .header {
    min-height: 95vh;
  }

  .greeting {
    margin-top: 10rem;
  }
</style>
