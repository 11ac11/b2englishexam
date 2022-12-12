<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="text-column">
	<h1>Hints, tips and advice to help you pass the Cambridge First B2 English exam.</h1>
	<p>The goal of B2FirstExam.com is to give clear and quick advice for the Cambridge First English exam, formally known as FCE.</p>
	<p>There's already a lot of sites doing this, but there's far too much to read. If you just want an easy to navigate site with quick tips, you're in the correct place.</p>
	<p>This is also an excellent source for teachers teaching First Certificate.</p>

	<h2>Exam Advice</h2>
	<p>On the menu at the top of the page, click any of the Reading/Use of English, Listening, Writing or Speaking options for more information and examples in this area.</p>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: flex-start;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

</style>
