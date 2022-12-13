<script>
  import SpeakingPart1 from "./SpeakingPart1.svelte"
  import SpeakingPart2 from "./SpeakingPart2.svelte"
  import SpeakingPart3 from "./SpeakingPart3.svelte"
  import SpeakingPart4 from "./SpeakingPart4.svelte"
</script>

<svelte:head>
  <title>About</title>
  <meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
  <h1>Speaking</h1>

  <h2>What's the Cambridge First Certificate Speaking exam like?</h2>

  <p>
    The FCE Speaking exam has four parts and takes around 14 minutes to
    complete:
  </p>
  <ol>
    <li><a href="/">Part 1 - Personal interview</a></li>
    <li>
      <a href="/"
        >Part 2 - Comparing two photographs (also called 'long turn')</a
      >
    </li>
    <li>
      <a href="/"
        >Part 3 - Discussion with a partner about a topic where you have come to
        a decision</a
      >
    </li>
    <li><a href="/">Part 4 - A conversation about themes from part 3</a></li>
  </ol>
  <p>
    There are two examiners in the room, one who asks you questions and one who
    marks you. You are tested on:
  </p>
  <ul>
    <li>fluency</li>
    <li>pronunciation</li>
    <li>range and appropriateness of language.</li>
  </ul>
</div>
<div class="transcript">
  <iframe
    width="560"
    height="315"
    src="https://www.youtube.com/embed/EdeZp0n0JHw"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
  />
</div>

<SpeakingPart1 />
<SpeakingPart2 />
<SpeakingPart3 />
<SpeakingPart4 />
