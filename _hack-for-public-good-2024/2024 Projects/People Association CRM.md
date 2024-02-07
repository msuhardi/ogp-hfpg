---
title: People Association CRM
permalink: /hack-for-public-good-2024/2024-projects/peopleassociationcrm/
variant: tiptap
description: ""
third_nav_title: 2024 Projects
---
<h3>People Association CRM</h3>
<h4>Problem</h4>
<p>PA is assisting a lot of residents with their financial difficulties through
the use of multiple funds. Currently, the routing and approval seeking
are manually done by the community officer (CO) at different community
centers. The problems with the current approach are:</p>
<ul>
<li>
<p>Arduous administrative process carried out by our COs using physical forms
and manually carrying forms around for signatures</p>
</li>
<li>
<p>No consistency between different community centers with regard to this
process</p>
</li>
<li>
<p>Data are not being digitally collected for better policy making</p>
</li>
</ul>
<h4>Solution</h4>
<ul>
<li>
<p>We use <a href="https://plumber.gov.sg" rel="noopener noreferrer nofollow" target="_blank">Plumber</a> (a
product developed by OGP for workflow automation) in combination with Zendesk
(for remote communication and approval seeking) and M365 (for data storage
and possible analysis)</p>
</li>
<li>
<p>In our design, we have 2 Plumber workflows:</p>
</li>
</ul>
<ol data-tight="true" class="tight">
<li>
<p>Application creation workflow:</p>
</li>
</ol>
<p>This starts with a FormSG that residents and COs use to raise a case.
The workflow, upon receiving the submission, will create a Zendesk ticket
and assign it to the CO. The workflow will also store the case inside a
shared M365 excel sheet for tracking</p>
<ol start="2" data-tight="true" class="tight">
<li>
<p>Approval workflow:</p>
</li>
</ol>
<p>CO will gather any extra information from resident (if needed) to add
to the case before forwarding to the relevant parties (also on Zendesk)
for explicit approval. Upon approval / rejection on Zendesk, the Plumber
workflow will update the case status to the tracking M365 sheet. The M365
sheet can be used to chart data and draw insights to make better policies.</p>
<p>Read more <a href="https://docs.google.com/presentation/d/1T5Crw7liZkdnR6Oa7U9365BV-I-66pstFv9g5xQz-zc/edit#slide=id.p" rel="noopener noreferrer nofollow" target="_blank">here</a>.</p>
<p></p>