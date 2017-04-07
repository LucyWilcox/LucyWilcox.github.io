---
layout: post
title: Black Duck GitHub Integration
description: Black Duck policy violations status pushed to GitHub
img: /img/github3.JPG
---

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/github3.JPG" alt="" title="example image"/>
</div>
<div class="col three caption">
	Checks if build failed due to Black Duck security or licensing violations within GitHub.  
</div>

<br>

I explored what types of integrations best used the areas of strength in Black Duck's solution to the issue of OSS security and license compliance. I proposed both a plan for GitHub Enterprise user who also subscribe to Black Duck's product and one for open source project owners who want to use Black Duck.

My solution for GitHub Enterprise users was to leverage Black Duck's plugin with Jenkins and Jenkin's plugin with GitHub to push status to GitHub. These status allowed users to see if each commit they push to GitHub and pull request they make passes or fails their Black Duck policies. I then went on to implement a proof of concept for this solution that engineering could verify and release.

I also proposed an integration for Open Source projects which uses Black Duck's OpenHub.net and Shields.io.

<b>What I learned: </b>
- Different users can require very different solutions.
- Creating a proof of concept makes it much easier for a project to be picked up and completed.  

<b>For: </b>Product Management at Black Duck Software

<b>During: </b>Summer 2016

<b>Collaborators: </b>Utsav Sanghani- PM at Black Duck

<b>Skills: </b>Jenkins, Java