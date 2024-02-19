---
title: Forge
permalink: /hack-for-public-good-2024/2024-projects/forge/
variant: tiptap
description: ""
third_nav_title: 2024 Projects
---
<h3>Forge</h3>
<h4>Problem</h4>
<p>Measuring productivity in software development teams is hard. Martin Fowler
famously wrote in 2003 that it was impossible to measure [1]. This makes
it hard for management to know if they can push teams, and hard for teams
themselves to understand if they are operating at a steady, but not quite
optimal state.</p>
<p>The past 25 years of software engineering have seen many developments,
from the adoption of agile practices, to the emergence of devops. In particular,
since 2014 the annual State of DevOps Report [2] surveys and tracks practices
and outcomes in thousands of teams across hundreds of organizations, large
and small in the hope of identifying patterns of highly effective and productive
teams.</p>
<p>Through these studies and surveys, some aspects of software delivery have
emerged as being highly correlated with effective teams delivering value
to their user and organization. This can be measured through 4 metrics,
dubbed the DORA metrics.</p>
<p><strong>What are the 4 DORA Metrics?</strong>
<br><strong>Deployment Frequency</strong> measures the number of times that
code is deployed into production. It’s usually reported in deployments
per day or per week.
<br><strong>Change Lead Time</strong> measures the time it takes from code being
committed to that code being released into production.
<br><strong>Change Failure Rate</strong> measures how often a code change  results
in a failure in production.
<br><strong>Time To Restore</strong> is the amount of time it takes a dev team to
recover from a failure in the system.</p>
<p>Why do tracking these matter? The 4 metrics are interconnected, and correlated
with the production stable and high quality software.</p>
<p>For example, when teams deploy often, it typically means they have small
chunk sizes for their deployments, and that they have high confidence in
their deployment processes. By having small chunks, the risks should be
well understood, and thus teams can respond in a targeted manner if issues
are seen. These should both reduce the number of incidents and the time
to restore.&nbsp;</p>
<p>Similarly, tracking failure rate and time to restore is important. Obviously,
incidents that impact users are undesirable and should be minimized, and
time dealing with incidents is time not used to deliver value to users.</p>
<h4>Solution</h4>
<p>Forge is an Internal Developer Portal (IDP) for OGP, which tracks the
4 DORA metrics for projects at OGP.&nbsp;</p>
<p>Forge provides information to OGP teams without expensive setups. The
project is feasible because teams at OGP all use git and github as their
revision control systems, and have similar automated ways to deploy their
project to production. Additionally, teams track incidents in a central
manner for shared learning.</p>
<p>Tracking DORA metrics can help drive conversations within teams. Team
can make educated decisions on what they could be focusing on next, and
they can monitor their progress.</p>
<p>For example, the metrics can be influenced by a variety of setups and
practices that teams can consider adopting. Here is a non-exhaustive list
below:</p>
<ul>
<li>
<p>Introduce automated test coverage</p>
</li>
<li>
<p>Automate deployments</p>
</li>
<li>
<p>Reduce chunk size</p>
</li>
<li>
<p>Reduce work parallelism</p>
</li>
<li>
<p>Implement feature flags</p>
</li>
<li>
<p>Set up robust monitoring and alerting</p>
</li>
<li>
<p>Train for incident response</p>
</li>
<li>
<p>Always run in-depth, blameless incident retrospectives</p>
</li>
</ul>
<p>Here are some product screenshots for Forge:</p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/Product___Products_List.png">
</div>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/Product___FormSG.png">
</div>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 100%" height="auto" width="100%" alt="" src="/images/Product___Plumber.png">
</div>
<p>The 4 DORA metrics are only proxy metrics to real value that software
development teams deliver to their organization and to their users. They
are also only a subset to deeper outcomes that can be measured. Forge as
a platform will hopefully be extended over time to allow teams to track
more of what they care about.</p>
<p><strong>Team members</strong>
<br>Kee Wei Lam, Software Engineer
<br>Tim Groleau, Software Engineer</p>
<p>Reference
<br>[1] <a href="https://martinfowler.com/bliki/CannotMeasureProductivity.html" rel="noopener noreferrer nofollow" target="_blank"><u>Cannot Measure Productivity </u></a>
<br>[2] <a href="https://dora.dev/" rel="noopener noreferrer nofollow" target="_blank"><u>State of DevOps Report</u></a>
</p>
<p></p>
<p></p>