---
layout: post
title: OSS Security on the Open Hub
description: a project with a background image
img: /img/VpV.JPG
---

I made Black Ducks’s OpenHub.com, a wiki for OSS, more aligned with the company’s direction by introducing project security information. First I explored site usage data, created user personas, and determined some high level use cases. I combined this with research on what information sources were available to us and how we could integrate with them to make a plan that my team member, Ashrith, and I could move forward with. We then developed proof-of-concepts for many different graphs.  
  
I then held demos and communicated with engineering, UI/UX, and marketing to select a final set of displays and a new, responsive, page layout. After writing detailed product specifications and users stories the rest of the Open Hub team started the development of the project.  
  
I also proposed, documented, and started implementation of an integration with GitHub in my last few weeks. 

What I learned:

- It's fine to spend time brainstorming and doing proof of concepts for a lot of ideas then throw most of them away and use what your learned.  
- How to architect a technical solution, though I won't be the implementing it all.  
- Though I planned what engineering would focused on, any decision I made impacted all departments - keep in communication with them. 
- Writing really really good JIRA tickets :)  

For: Product Management at Black Duck Software

During: Summer 2016

Collaborators: Ashrith Bangi- Software Development Intern 

Skills: Highcharts, user workflows, mock-ups, OmniGraffle, documentation, Jira

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/Width1366Finalv3.png" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/Width1366ProjectSecurity.png" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/SS2.png" alt="" title="example image"/>
</div>
<div class="col three caption">
	Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/5.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	This image can also have a caption. It's like magic. 
</div>

You can also put regular text between your rows of images. Say you wanted to write a little bit about your project before you posted the rest of the images. You describe how you toiled, sweated, *bled* for your project, and then.... you reveal it's glory in the next row of images.


<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/img/6.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/11.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


<br/><br/><br/>


The code is simple. Just add a col class to your image, and another class specifying the width: one, two, or three columns wide. Here's the code for the last row of images above: 

	<div class="img_row">
	  <img class="col two" src="/img/6.jpg"/>
	  <img class="col one" src="/img/11.jpg"/>
	</div>
