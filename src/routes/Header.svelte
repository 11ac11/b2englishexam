<script>
	import { page } from '$app/stores';
</script>

<header>
	<div class="corner">
		<h1>B2 English Exam</h1>
	</div>

	<nav>
		<ul>
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
				<a href="/">Home</a>
			</li>
			<li aria-current={$page.url.pathname === '/reading-use-of-english' ? 'page' : undefined}>
				<a href="/reading-use-of-english">Reading & Use of English</a>
			</li>
			<li aria-current={$page.url.pathname === '/writing'  ? 'page' : undefined}>
				<a href="/writing">Writing</a>
			</li>
			<li aria-current={$page.url.pathname === '/listening'  ? 'page' : undefined}>
				<a href="/listening">Listening</a>
			</li>
			<li aria-current={$page.url.pathname === '/sistening'  ? 'page' : undefined}>
				<a href="/speaking">Speaking</a>
			</li>
		</ul>
	</nav>

</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	.corner {
		width: fit-content;
		height: 3em;
	}

	.corner h1 {
		margin: 0;
		text-decoration: none;
	}

	nav {
		display: flex;
		justify-content: center;
		background-color: var(--color-theme-1);
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	li[aria-current='page']::before {
		--size: 6px;
		content: '';
		width: 0;
		height: 0;
		position: absolute;
		top: 0;
		left: calc(50% - var(--size));
		border: var(--size) solid transparent;
		border-top: var(--size) solid var(--color-theme-1);
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 0.5rem;
		color: var(--color-text);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}

	a:hover {
		color: #FFF;
	}
</style>
