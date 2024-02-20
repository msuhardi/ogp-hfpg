---
title: Telegov
permalink: /hack-for-public-good-2024/2024-projects/telegov/
variant: tiptap
description: ""
third_nav_title: 2024 Projects
---
<h3>Telegov</h3>
<h4>Problem</h4>
<p>Telegram is a great platform for building applications in the form of
bots, allowing developers to focus on business logic and not worry about
ancillary matters, like frontend design. This makes it very useful for
the rapid development of internal, non-sensitive applications for public
officers. However, we do not have a way to authenticate Telegram users
as public officers, which is important when controlling access to internal
information and features.</p>
<h4>Solution</h4>
<p>Telegov provides a template codebase to build Telegram bots for internal
non-sensitive use cases in government. It does this by integrating sgID
to authenticate users as Singapore Government public officers. Examples
of intended use cases include gating access to internal Telegram groups
or resources.</p>
<p>The template can be found <a href="https://github.com/opengovsg/telegovsg" rel="noopener noreferrer nofollow" target="_blank">here</a> and a Vercel-ready
Telegram bot that gatekeeps Telegram groups can be found <a href="https://github.com/opengovsg/telegovsg-bouncer" rel="noopener noreferrer nofollow" target="_blank">here</a>.
The codebase could be modified to control access based on other sgID profile
fields, eg, using addresses for a residents-only Telegram bot.</p>
<p>Given that Telegov is a developer kit, we have yet to test this with potential
users who may want to build their own Telegram bots for Government use.
We would like to encourage those with potential use cases for Telegov to
get in touch with us.</p>
<h4>Team</h4>
<p>Alwyn Tan
<br>Cheri Ong
<br>Alexander Lee
<br>Kathleen Koh
<br>Koh Jia Cheng</p>
<p></p>
<p></p>