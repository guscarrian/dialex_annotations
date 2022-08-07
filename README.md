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


| words              | transform to | keepUpperCase is false | keepUpperCase is true |  
|--------------------|--------------|------------------------|-----------------------|  
| "XML HTTP request" | pascalCase   | `XmlHttpRequest`       | `XMLHTTPRequest`      |  
| "new customer ID"  | camelCase    | `newCustomerId`        | `newCustomerID`       | 



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
    <td class="tg-0pky">S: ¿Cómo se llama? &lt;What is the name?&gt;</td>
  </tr>
  <tr>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky">S: ¿Cómo es? &lt;How is it?&gt;</td>
  </tr>
  <tr>
    <td class="tg-0pky">AskL2</td>
    <td class="tg-0pky">SUB asks for a word&nbsp;&nbsp;using L2</td>
    <td class="tg-0pky">S: What is the name?</td>
  </tr>
</tbody>
</table>
