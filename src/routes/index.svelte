<script>
	import { Styles } from 'sveltestrap';
</script>

<Styles />
<header class="header">
	<div class="greeting px-4">
		<div>{"Hello, There. I'm"}</div>
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
