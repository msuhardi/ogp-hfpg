---
title: Scribe
permalink: /hack-for-public-good-2024/2024-projects/scribe/
variant: tiptap
description: ""
third_nav_title: 2024 Projects
---
<h3>Scribe</h3>
<h4>Problem</h4>
<p>Medical Social Workers (MSWs) meet needy patients daily to understand
their personal backgrounds, financial circumstances, and social / medical
issues, so as to provide an overall psycho-social assessment of the patient
and to apply for financial assistance on their behalf.</p>
<p>These meetings are typically 1 hour long, after which MSWs must spend
time documenting and consolidating their notes on the patient. Writing
these case notes can take between 30 mins to 2 hours, depending on the
case complexity and the experience of the MSW. The average MSW may see
between 3 to 8 patients in a day, depending on seniority and specialty.</p>
<h4>Solution</h4>
<p>We built <strong>Scribe </strong>to help Medical Social Workers (MSWs)
synthesise MSW-Patient conversations into structured progress notes.&nbsp;</p>
<p>Scribe allows MSWs to record their conversations with patients, after
which a multi-lingual transcript (with support for English, Malay, Chinese,
and Singlish) is generated using state-of-the-art speech recognition models.&nbsp;</p>
<p>Using this transcript, MSWs can then generate a summary of the transcript
with a chosen output type, such as actionables in bullet points or a summary
with section headings. A large language model (LLM) processes and summarises
this transcript with the desired output type.</p>
<p>Both the speech recognition model and LLM are open-source models running
on our infrastructure and we rely on no external APIs for Scribe, so sensitive
patient data and conversations never leave our system.</p>
<p>The generated summary can then be exported directly to Care360 as a draft
case note. (Care360 is a patient management system used by MSWs and is
the key driver for their daily workflows.) On Care360, MSWs can further
edit the case note to their satisfaction. By transcribing and summarising
MSW-patient conversations and providing MSWs with a solid foundation to
swiftly compose their notes, Scribe speeds up the note-writing process
and enables MSWs to prioritize what truly matters—fostering meaningful
connections and enhancing patient care.</p>
<p>For more details on the Scribe prototype and the team behind it, <a href="https://docs.google.com/presentation/d/16QDvSIQ6UdnYeybOe0AVQMBcvDnilKTs-NI-Y_WbkR0/edit?usp=sharing" rel="noopener noreferrer nofollow" target="_blank"><u>take a look at our slideshow presentation</u></a>.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/A2_Poster_page_0001.jpeg">
</div>
<p></p>