# Annotated dialogue excerpts
This repository contains a collection of 40 annotated dialogue excerpts for a thesis project. They are extracted from two different second language learner spoken corpora: 

- ESF: European Science Foundation Second Language Databank
- BELC: Barcelona English Language Corpus

## Format and possible changes
It should be noted that, since the dialogue excerpts come from different corpora, there might be some differences when it comes to the transcription format. In order to formalize the transcripts, the ESF format will be used as reference since most of the excerpts comes from this corpus. That is to say, the transcriptions will be lowercased and additional non-verbal sounds such as laughter or pauses in speech will also be annotated. The original transcripts were not altered, except for speeling corrections (i.e., *'tragetto' --> 'traghetto') and the addition of English translations whenever they were not provided. 

## Taxonomy
The dialogue extracts were manually annotated using a taxonomy of dialogue acts created for the purpouse of this work. It is based on previous related taxonomies (Varonis and Gass, 1985; Bondarenko, 2019; Myrendal, 2019). The table below shows the dialogue act annotation schema.

Note the following abbreviations:
- S, S1, S2: speaker
- INV: Investigator (teacher)
- SUB: Subject (learner)
- L1: learner’s first language
- L2: target language that learner is acquiring
- M: word or phrase in L2 that learner is missing


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Tag</th>
    <th class="tg-0pky">Description</th>
    <th class="tg-0pky">Example utterances</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">AskL1</td>
    <td class="tg-0pky">SUB asks for word using L1</td>
    <td class="tg-0pky">S: ¿Cómo se llama? &lt;What is the name?&gt;<br><br><span style="font-weight:400;font-style:normal">S: ¿Cómo es? &lt;How is it?&gt;</span></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="2">AskL2</td>
    <td class="tg-0pky" rowspan="2">SUB asks for a word&nbsp;&nbsp;using L2</td>
    <td class="tg-0pky" rowspan="2">S: What is the name?</td>
  </tr>
  <tr>
  </tr>
  <tr>
    <td class="tg-0pky">IndAskL1</td>
    <td class="tg-0pky">SUB indirectly asks for a word&nbsp;&nbsp;using L1</td>
    <td class="tg-0pky">S: no sé el nombre &lt;I don’t know the name&gt;<br><br><span style="font-weight:400;font-style:normal">S: no sé cómo se dice &lt;I don’t know how to say it&gt;</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">IndAskL2</td>
    <td class="tg-0pky">SUB indirectly asks for a word&nbsp;&nbsp;using L2</td>
    <td class="tg-0pky">S: I don’t know what the name is.<br><br><span style="font-weight:400;font-style:normal">S: I don’t remember how to say the word.</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">SearchL2</td>
    <td class="tg-0pky">SUB (unsuccessfully) searches for <span style="font-weight:400;font-style:normal">a </span><br><span style="font-weight:400;font-style:normal">word or phrase in L2</span></td>
    <td class="tg-0pky">S: The price of food is... eer... is...<br><br><span style="font-weight:400;font-style:normal">S: I only read books and... er...</span><br><br><span style="font-weight:400;font-style:normal">S: We bought tomatoes and... mm...</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">ProvL1</td>
    <td class="tg-0pky">SUB provides the L1 translation of M</td>
    <td class="tg-0pky">S: ...mesa &lt;table&gt;<br><br><span style="font-weight:400;font-style:normal">S: ...¿niña? &lt;girl?&gt;</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">ProvL2</td>
    <td class="tg-0pky">INV provides M in L2</td>
    <td class="tg-0pky">S: It’s called a table.</td>
  </tr>
  <tr>
    <td class="tg-0pky">ProvDesL2</td>
    <td class="tg-0pky">SUB describes M in L2</td>
    <td class="tg-0pky">S: This thing you use for brushing your hair</td>
  </tr>
  <tr>
    <td class="tg-0pky">Rep</td>
    <td class="tg-0pky">INV&nbsp;&nbsp;repeats M</td>
    <td class="tg-0pky">L: Mobile phone<br><br><span style="font-weight:400;font-style:normal">T: Mobile phone &lt;--</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">Test</td>
    <td class="tg-0pky">SUB tries pronouncing M</td>
    <td class="tg-0pky">T: It’s called a sprinkling can.<br><br><span style="font-weight:400;font-style:normal">L: Sprinkling can. &lt;--</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">TestC</td>
    <td class="tg-0pky">SUB tries using M in context</td>
    <td class="tg-0pky">T: It’s called a sprinkling can.<br><br><span style="font-weight:400;font-style:normal">L: We took the sprinkling can to water the plants. &lt;--</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">Ack</td>
    <td class="tg-0pky">S2 acknowledges previous utterance by S1</td>
    <td class="tg-0pky">S1: We went to the park on Friday.<br><br><span style="font-weight:400;font-style:normal">S2: mhm</span></td>
  </tr>
</tbody>
</table>