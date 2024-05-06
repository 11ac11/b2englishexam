<script>
  import ListeningPart1 from "./ListeningPart1.svelte"
  import ListeningPart2 from "./ListeningPart2.svelte"
  import ListeningPart3 from "./ListeningPart3.svelte"
  import ListeningPart4 from "./ListeningPart4.svelte"
</script>

<svelte:head>
  <title>Listening</title>
  <meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
  <h1>Listening</h1>

  <h2>What's the Cambridge First Certificate Listening exam like?</h2>

  <p>The test has four sections and takes about 40 minutes:</p>
  <ol>
    <li>
      <a href="#part-1">Part 1 - listen to 8 recordings (one question each)</a>
    </li>
    <li>
      <a href="#part-2">Part 2 - complete gapped sentences</a>
    </li>
    <li>
      <a href="#part-3">Part 3 - 5 speakers and multiple matching</a>
    </li>
    <li>
      <a href="#part-4">Part 4 - long recording (7 multiple choice questions)</a
      >
    </li>
  </ol>
  <p>You get one point for each correct answer.</p>
  <p>
    You will hear the audio twice. There is likely to be a variety of ages and
    accents (think Scottish, South African, Australian, Irish etc.) so the best
    way to prepare is to listen to as many as possible. Try watching
    films/series and listening to the radio/podcasts in English.
  </p>
</div>

<ListeningPart1 />
<ListeningPart2 />
<ListeningPart3 />
<ListeningPart4 />
