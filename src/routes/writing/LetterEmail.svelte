<script lang="ts">
	import src from '$lib/examples/First-Certificate-Writing-Part-1-Essay.png';
  export let writingState;
</script>

<div class="exam-part">
  <div class="back"><button on:click={()=>writingState=''}>back</button></div>
  <div class="text-column">
    <h1>Essay</h1>
    <h2>How to write an essay well in the First Certificate B2 exam</h2>
    <p>Writing an essay is a compulsory task in Writing part 1. This means everyone must write an essay to pass FCE. Luckily, it isn't too difficult to write a good essay.</p>

    <h2>Quick tips for writing an essay</h2>
    <ul>
      <li>5 paragraphs</li>
      <li>Rhetorical question in the introduction</li>
      <li>Try to write in passive voice - avoid using 'I', 'me' and 'my'</li>
      <li>Formal, no contractions</li>
      <li>Explain your points. If you talk about something negative, offer a solution.</li>
      <li>Use high level connectors (however, although, in addition, despite this, yet etc.)</li>
      <li>Use sequencers (First of all, secondly, finally, In conclusion).</li>
    </ul>
    <p style={'text-align: center; font-size: 2rem;'}>↓</p>
  </div>
</div>
<div class="example">
  <div class="text-column">
    <h1>Example Question</h1>
    <img {src} alt={'Example question writing part 1'}>
    <h1>Structure</h1>
    <p>I've provided an example layout/structure to the right of this paragraph. I recommend using one-line spaces between paragraphs in all writing exams.</p>
    <h2>First block: Title (optional)</h2>
    <h2>Paragraph 1: Introduction</h2>
    <p>It is a good idea to put some present perfect here. e.g.</p>
    <ul>
      <li>... has become more/less important in our modern society</li>
      <li>... has been a vital part of our lives for many years</li>
      <li>... hasn't been that useful throughout history yet…</li>
    </ul>

    <p>Use a rhetorical question to end your introduction.</p>

    <h2>Paragraph 2: Point 1</h2>
    <p>Start with a sequencer: First of all / To begin with / Firstly</p>
    <p>Use a high level connector: although / even though / despite / yet / in contrast / whereas</p>

    <h2>Paragraph 3: Point 2</h2>
    <p>Start with another sequencer: Secondly / A second idea(/issue) / Another idea(/issue)</p>
    <p>Use a DIFFERENT high level connector (see paragraph 2)</p>

    <h2>Paragraph 4: Point 3</h2>
    <p>Start with another sequencer: Third of all / thirdly / The third issue(/idea) / Finally</p>
    <p>Use another DIFFERENT high level connector (see paragraph 2) (You should use at least 3 different high level connectors in your essay)</p>

    <h2>Paragraph 5: Conclusion</h2>
    <p>Start with the final sequencer: To conclude / In conclusion</p>
    <p>Try to link back to the exam question, write the question again using different words.</p>
  </div>
</div>