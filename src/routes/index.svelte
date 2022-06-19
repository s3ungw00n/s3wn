<svelte:head>
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css"
  />
  <link
    rel="stylesheet"
    as="style"
    crossorigin="true"
    href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard-dynamic-subset.css"
  />
  <style>
    body {
      font-family: Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto,
        'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic',
        'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', sans-serif;
    }
  </style>
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
    <div class="text-secondary">Fullstack Web Developer</div>
    <div class="mt-2">
      <a href="https://blog.s3wn.com" target="_blank">Blog</a>
      <a href="https://github.com/s3ungw00n" target="_blank">Github</a>
      <a href="https://twitter.com/s3ungw00n" target="_blank">Twitter</a>
    </div>
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
