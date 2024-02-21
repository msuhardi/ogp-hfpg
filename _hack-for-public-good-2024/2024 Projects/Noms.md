---
title: Noms
permalink: /hack-for-public-good-2024/2024-projects/noms/
variant: tiptap
description: ""
third_nav_title: 2024 Projects
---
<h3>Noms by Pair</h3>
<h4>No More Grunt (Knowledge) Work</h4>
<p>Drafting of meeting minutes, or Notes of Meetings (NOMs), within the government
is a highly nuanced but tedious task. It can take anywhere from a few hours
to a full civil servant’s work day. As part of the Pair suite, Noms draws
from your meeting agendas, materials and recordings to create Government-style
minutes, in <s>days/hours</s> minutes.</p>
<h4>Why Meeting Minutes?</h4>
<p>With the launching of products such as Pair Chat and Pair Intern, we see
a big uptake in LLM-centric products amongst civil servants.</p>
<p>While these products are good for creative and rudimentary tasks such
as drafting an initial policy paper or summarising information, there are <strong>limitations with addressing tasks with a defined expected output</strong>.
Part of the problem is that we could not fine-tune the model according
to a given task, as there is a lack of input-labeled output pairs or a
concrete set of metrics for a given specific domain. That being said, there
is one specific use-case we found in the government that fulfils this use
case - Government Meeting Minutes.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/A3.jpeg">
</div>
<h4>But really, why Meeting Minutes?</h4>
<p>Meetings are an interesting paradox - on one hand they are crucial to
an organization. On the other hand, they are painful, tedious, and frustratingly
long.</p>
<p>One major pain that comes out of meetings is the writing of meeting minutes,
or NOMs. This is work that is synonymous with government officers. It takes
up a lot of officers’ valuable time both in and out of work to meet the
deadlines.</p>
<p>Thus far, current solutions have focused more on improving the transcription
process - a supplementary aid rather than the work at hand. We are not
interested in simply converting speech to text. Instead, our focus is the
actual work secretariats have to perform. We aim to write public-style
meeting minutes as well as the best human officers by:</p>
<ul>
<li>
<p>Writing good, factual, stylistically consistent minutes</p>
</li>
<li>
<p>Processing information captured during the meeting</p>
</li>
<li>
<p>Checking it against supporting documents or other forms of “institutional
knowledge”</p>
</li>
<li>
<p>Coming up with the minutes in the appropriate format and lingo (e.g. Director
A states … Deputy Director B to follow up with action …)</p>
</li>
</ul>
<p>When done right, this will not only save the government hundreds of man-hours
every week, but allow meetings to be more focused and organized.&nbsp;</p>
<h4>Opportunity and Impact</h4>
<p>Noms was prototyped during OGP’s Hack for Public Good 2024 Hackathon.
The team has piloted it in meetings within government agencies, and has
drastically reduced the time taken to generate minutes by up to 80%. The
team has since been asked to provide further use of Noms to support upcoming
meetings.</p>
<p>"<strong><em>We would really like to continue using it for our subsequent meetings!</em></strong>" <em>- Public Officer from Ministry</em>
</p>
<p>"<strong><em>The generated draft is good and managed to capture specific terminologies used.</em></strong>"<em> - Officer from Government Statutory Board</em>
</p>
<p>"<strong><em>My sense is that the draft is almost there and that the minutes generated has a good accuracy of what was captured during the meeting!</em></strong>" <em>- Officer from Government Statutory Board</em>
</p>
<p>With a high demand from multiple agencies across the government, Noms
is expanding its pilot to various other ministries and statutory agencies
(e.g. MCI, TTSH, PSD).</p>
<h4>Building the Noms</h4>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/noms_replace.jpeg">
</div>
<p>Noms generates meeting minutes through multiple steps:&nbsp;</p>
<ul data-tight="true" class="tight">
<li>
<p>Transcription</p>
</li>
<li>
<p>Segmentation</p>
</li>
<li>
<p>Contextualisation</p>
</li>
<li>
<p>Summarization and styling</p>
</li>
</ul>
<p>The transcription step first makes use of a high-performing, self-hosted
variant of OpenAI’s Whisper model to generate a transcript with proper
speaker diarization.&nbsp;</p>
<p>The transcription then goes through a segmentation layer, which allocates
different parts of the transcript to the corresponding agenda item. The
segmentation step currently assumes that transcript chunks for each agenda
item are continuous and independent of one another (ie; agenda items are
done sequentially and not mixed around). These assumptions were made partly
from the initial user testing sessions we had with some of our agency partners.&nbsp;</p>
<p>In order to further improve accuracy and to provide additional context
to a meeting, the contextualisation layer is added, where specific supporting
document pages are correlated to the respective transcription chunk. Contextualisation
is done by first indexing the agenda item slides, followed by a probabilistic
semantic scoring mechanism that ensures each transcript segment is rightfully
pegged to the correct page range of a supporting document.</p>
<p>At this stage, each agenda item is pegged to a transcript, of which transcript
chunks are contextualized with the relevant page range in the agenda item’s
supporting document. Summarisation and styling is then performed on all
this information through prompt engineering to generate the draft meeting
minutes.</p>
<p>The prototype was built based on recent strategies in LLM and prompting
optimisation. These strategies would allow the entire pipeline to be easily <em>trainable </em>to
specific contexts and use cases. In the next few weeks, the team will be
looking into better improving the personalisation for Noms, to get your
meeting minutes<em> in your style.</em>
</p>
<div class="iframe-wrapper">
<iframe allowfullscreen="true" frameborder="0" src="https://www.youtube.com/embed/KQUqp37Xz-I?si=skoBbFUEtHgDz2k8"></iframe>
</div>
<h4>Meet the Nomies</h4>
<p>The prototype was developed by the following team.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/teamPhoto.jpeg">
</div>
<h4>What's Next?</h4>
<p>Noms is constantly being enhanced. Some features would include automating
factuality checks for the generated meeting minutes, improving referencing
to all meeting material uploaded, as well as integrating with the current
modes of holding meetings.&nbsp;</p>
<p>Given the nuanced nature of different agencies, one possible route is
developing bespoke minutes generators which differ based on the style and
preferences of your organization. The team is also looking into making
Noms accessible to higher data classification and sensitivity level meetings.&nbsp;</p>
<h4>Bigger Picture</h4>
<p>The bigger picture is that we believe this generation of AI (e.g. LLMs)
can actually accomplish knowledge work end to end, which was not possible
with previous tech. Work could get simpler, and higher quality. We are
doing Pair Noms to build capability to do that – taking in finished work
product and input materials, and learning how to tune underlying models
to produce the high-quality work we expect to depend on.</p>
<p>If you're currently a secretariat, or have a meeting in mind to try out
Noms, sign up for our pilot <a href="https://go.gov.sg/nomnoms" rel="noopener noreferrer nofollow" target="_blank"><u>here</u></a>!</p>
<p></p>