---
title: Fireside
permalink: /hack-for-public-good-2024/2024-projects/fireside/
variant: tiptap
description: ""
third_nav_title: 2024 Projects
---
<h2>Fireside</h2>
<div class="iframe-wrapper">
<iframe height="569" width="960" allowfullscreen="true" frameborder="0" src="https://docs.google.com/presentation/d/e/2PACX-1vQvRdjnri6QUMGvfIYP7NGg0BJUuOD3OUgkOGz7mATwm4rB0cqdNxt3qkX3z5cqRUYHuq3lJq9cs7pH/embed?start=false&amp;loop=false&amp;delayms=3000"></iframe>
</div>
<h3>Problem</h3>
<p>Work burnout is associated with a higher likelihood of physical and psychological
health problems¹. More young adults are facing work burnout, with 57% of
Singaporeans reporting that burnout was the leading factor affecting their
mental health².</p>
<div class="isomer-image-wrapper">
<img style="width: 60%;" height="auto" width="100%" alt="" src="/images/Burnout_infographic.png">
</div>
<h3>Solution</h3>
<p>Fireside is a web app that tackles the growing problem of work burnout
among young working adults.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/Fireside_app_screenshot.png">
</div>
<p>1. Assess your work stressors to find out your <strong>biggest occupational risk factors</strong>
</p>
<p>2. Chat with Flamey, our friendly chatbot, to <strong>share your work rants anonymously and securely</strong>
</p>
<p>3. Let Flamey convert work rants into <strong>constructive feedback</strong> for
managers, teammates or HR</p>
<p>4. Explore self-help resources to <strong>manage work burnout symptoms</strong> 
</p>
<p>Flamey the chat bot is powered by <strong>ChatGPT 3.5</strong>, and has
been engineered to follow a conversation flow that models after the <strong>Cognitive Behavioural Therapy</strong> framework.
This framework aims to identify and challenge negative thought patterns
and behaviours to promote healthier cognitive and emotional responses.</p>
<p>Work stressors are assessed using the UK HSE Management Standards quiz,
a <strong>psychometrically verified measure of work-related stress</strong>³,
to inform the user of their main risk factors for burnout. The user can
then bring these results to Flamey to address them, or find out more.</p>
<p>
<br>Try out the prototype <a href="https://go.gov.sg/hfpg-fireside" rel="noopener noreferrer nofollow" target="_blank"><u>here</u></a>!</p>
<h2>Webapp Features</h2>
<h3>Chat Bot</h3>
<p>The key feature of Fireside is a chatbot. The chatbot is built on ChatGPT
3.5, but we aim to add value compared to just talking to ChatGPT. The chatbot
aims to be more friendly and helpful by using therapeutic methods, as well
as to provide some practical aid to the user.
<br>
</p>
<p>There are two main chat flows that the bot will use, which is either to:</p>
<ul>
<li>
<p>Just be a listening ear to the user</p>
</li>
<li>
<p>Help the user turn rants into constructive feedback for others</p>
</li>
</ul>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 50%;" height="auto" width="100%" alt="" src="/images/Fireside_Chat.jpeg">
</div>
<p>At the beginning of the chat, the chatbot will ask the user which of the
following flows they would like to enter, after which it will use the respective
flow. Both flows will use distinct ChatGPT prompts.&nbsp;</p>
<p>The listening ear flow is guided with a prompt that attempts to follow
cognitive behavioural therapy, empathizing but questioning the user’s negative
views.</p>
<p>The rant to constructive feedback flow is guided by a prompt that gets
details from the user about their work difficulties, and then turns them
into e.g. a message or email, which you can iterate on and eventually send
to your colleagues.</p>
<p>For more details, please refer to the slides above.</p>
<h3>Anonymous Login</h3>
<p>We found that one of the major asks from users was anonymity. Mental health
is a sensitive topic, and users want to know that their privacy is protected.
<br>
</p>
<p>For Fireside, we opted for the approach that we never ask for any of the
user’s personal information that could identify them. When the user first
enters the site, we generate a secret key for them, which they can use
to come back to their chats in the future. This way, the user can keep
their chat and quiz history, while their identity is never revealed.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/Fireside___anonymous_login.png">
</div>
<h3>Self Assessment for Stressors</h3>
<p>We provide a self assessment for the main work stressors that a user faces.
This is a 35 question quiz provided by the UK HSE, called the Management
Standards Indicator tool. It is a psychometrically verified measure of
work-related stress² that users can use to assess their main stressors.
After they are done, they can bring their results to the chat bot, and
the chat bot will have the user’s result as a context for their conversation.</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/Fireside___quiz.png">
</div>
<h3>User feedback</h3>
<p>Through user testing with young working adults, we found the following
aspects of Fireside that worked well for users:
<br>
</p>
<ul data-tight="true" class="tight">
<li>
<p><strong>It makes users feel heard</strong>: "I think Flamey’s responses
are pretty validating and they make me feel heard.”</p>
</li>
<li>
<p><strong>It is like chatting with real person: </strong>"It's pretty smart
and compares well with chatting with a real person."</p>
</li>
<li>
<p><strong>Reflective prompts were good:</strong> “When chatting with the
bot I like that it prompts me to elaborate. Interesting. Also tries to
CBT me as well. I have no issues with the bot responses.”</p>
</li>
<li>
<p><strong>Diversity of Resources: </strong>“I appreciate how the resources
<br>are very diverse.”</p>
<p></p>
</li>
</ul>
<p>We also learned about the following areas that we should improve on:</p>
<ul data-tight="true" class="tight">
<li>
<p><strong>Improve conversation dynamics and moderation</strong>
</p>
</li>
<li>
<p><strong>Improve user assurance</strong>
</p>
</li>
<li>
<p><strong>Expand therapeutic repertoire</strong>
</p>
</li>
<li>
<p><strong>Provide personalised responses and user journey</strong>
</p>
</li>
</ul>
<h3>Potential Impact</h3>
<p>The potential impact of a mental health intervention which will be freely
accessible to the community include:
<br>
</p>
<ul>
<li>
<p><strong>Accessibility and Reach: </strong>The chatbot and resources provide
a low-barrier entry point for individuals to seek mental health support,
which can reach a wider audience, including those who may not have had
access to mental health resources before.</p>
</li>
<li>
<p><strong>Early Intervention and Prevention: </strong>The chatbot can facilitate
early intervention, to help prevent the escalation of issues, leading to
better long-term outcomes for the community.</p>
</li>
<li>
<p><strong>Empowerment and Education: </strong>Through the app, individuals
can access information, coping strategies, and self-help resources, empowering
them to take an active role in managing their mental well-being. This can
contribute to a more informed and resilient community.</p>
</li>
<li>
<p><strong>Reduced Stigma and Barriers: </strong>By offering an anonymous
platform for seeking support, the chatbot can help reduce the stigma associated
with mental health and break down barriers to seeking help. This can encourage
more individuals to proactively address their mental well-being.</p>
</li>
</ul>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/Fireside.png">
</div>
<p>Left to right: Yihan Liao (Marketing), Louiz Kim-Chan (Engineering), Jasmine
Ang (Engineering), Lynette Lee (Design), Shannen Ho (Marketing)</p>
<h3>Contact Us</h3>
<p>For any queries or collaborations, email us at <a href="https://go.gov.sg/hfpg-fireside" rel="noopener noreferrer nofollow" target="_blank"><u>fireside@open.gov.sg</u></a>.</p>
<h3>References</h3>
<p>¹ Nadon L, De Beer LT, Morin AJS. Should Burnout Be Conceptualized as
a Mental Disorder? Behav Sci (Basel). 2022 Mar 17;12(3):82. doi: 10.3390/bs12030082.
PMID: 35323401; PMCID: PMC8945132. (Link)
<br>
<br>² Tham, D. (2022, October 8). Burnout, not COVID-19 restrictions, most
affected mental health in Singapore during the pandemic. Channel News Asia.
Retrieved from <a href="https://www.channelnewsasia.com/singapore/burnout-mental-health-workers-employees-pandemic-2972961" rel="noopener noreferrer nofollow" target="_blank">https://www.channelnewsasia.com/singapore/burnout-mental-health-workers-employees-pandemic-2972961</a>
</p>
<p>³ K. Brookes, C. Limbert, C. Deacy, A. O’Reilly, S. Scott, K. Thirlaway,
Systematic review: Work-related stress and the HSE Management Standards,
Occupational Medicine, Volume 63, Issue 7, October 2013, Pages 463–472,
<a href="https://doi.org/10.1093/occmed/kqt078(Link)" rel="noopener noreferrer nofollow" target="_blank">https://doi.org/10.1093/occmed/kqt078(Link)</a>
</p>