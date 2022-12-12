<script lang="ts">
	import Article from "./Article.svelte";
	import Essay from "./Essay.svelte";
	import LetterEmail from "./LetterEmail.svelte";
	import Report from "./Report.svelte";
	import Review from "./Review.svelte";

	import { fade, fly } from "svelte/transition";

	let writingState:string = '';

</script>
<svelte:head>
	<title>Writing</title>
	<meta name="description" content="Information about the writing part of the Cambridge First Certificate English exam" />
</svelte:head>

{#if writingState == ''}
<div class="text-column" in:fade={{delay: 0, duration: 400}}>
	<h1>Writing</h1>

	<h2>What's the Cambridge First Certificate Writing exam like?</h2>

	<p>The writing test has two parts and takes around 80 minutes:</p>

	<ol>
		<li>Part 1 - write an <a on:click={() => writingState = 'essay'}>essay</a>
		<li>
			Part 2 - you have to choose one of 4 options, the options could be: an <a on:click={() => writingState = 'article'}>article</a>, an essay, a
			<a on:click={() => writingState = 'letter'}>letter/email</a>, a <a on:click={() => writingState = 'report'}>report</a>, a <a on:click={() => writingState = 'review'}>review</a>.
		</li>
	</ol>
	<p>Each question has 20 maximum marks, 5 marks for each category:</p>

	<ul>
		<li>Content</li>
		<li>Communicative Achievement</li>
		<li>Organisation</li>
		<li>Vocabulary/grammar</li>
	</ul>
	<p>
		All questions have a word count of 140-190 words, although 190 is the maximum, if you write up
		to 200 words you should be fine (no examiners sit and count all the words, but if it seems too
		long or too short, they will notice!)
	</p>
</div>
{:else if writingState == 'essay'}
<div class="fly" in:fly={{ y: 200, duration: 1000}}>
	<Essay bind:writingState={writingState}/>
</div>
{:else if writingState == 'letter'}
<div class="fly" in:fly={{ y: 200, duration: 1000}}>
	<LetterEmail bind:writingState={writingState}/>
</div>
{:else if writingState == 'article'}
<div class="fly" in:fly={{ y: 200, duration: 1000}}>
	<Article bind:writingState={writingState}/>
</div>
{:else if writingState == 'report'}
<div class="fly" in:fly={{ y: 200, duration: 1000}}>
	<Report bind:writingState={writingState}/>
</div>
{:else if writingState == 'review'}
<div class="fly" in:fly={{ y: 200, duration: 1000}}>
	<Review bind:writingState={writingState}/>
</div>
{/if}
