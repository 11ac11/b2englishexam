<script>
  import ReadingPart1 from "./ReadingPart1.svelte"
  import ReadingPart2 from "./ReadingPart2.svelte"
  import ReadingPart3 from "./ReadingPart3.svelte"
  import ReadingPart4 from "./ReadingPart4.svelte"
  import ReadingPart5 from "./ReadingPart5.svelte"
  import ReadingPart6 from "./ReadingPart6.svelte"
  import ReadingPart7 from "./ReadingPart7.svelte"
</script>

<svelte:head>
  <title>About</title>
  <meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
  <h1>Reading & Use of English</h1>

  <h2>
    What's the Cambridge First Certificate Reading and Use of English exam like?
  </h2>

  <p>The test has seven sections and takes 75 minutes:</p>
  <ol>
    <li><a href="/">Part 1 - multiple choice cloze</a></li>
    <li><a href="/">Part 2 - open cloze, text with gaps</a></li>
    <li><a href="/">Part 3 - word formation</a></li>
    <li><a href="/">Part 4 - key word transformations</a></li>
    <li><a href="/">Part 5 - text with 6 multiple choice questions</a></li>
    <li><a href="/">Part 6 - text with 6 sentences missing</a></li>
    <li><a href="/">Part 7 - multiple matching, 10 questions</a></li>
  </ol>
</div>

<ReadingPart1 />
<ReadingPart2 />
<ReadingPart3 />
<ReadingPart4 />
<ReadingPart5 />
<ReadingPart6 />
<ReadingPart7 />
