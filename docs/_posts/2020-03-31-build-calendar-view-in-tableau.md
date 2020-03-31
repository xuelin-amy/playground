---
title: Build a calendar view in Tableau
excerpt: this is a step-by-step guide on how to build calendar view in tableau using NYC taxi trips data from Kaggle.
categories: 
  - Tableau
  - visualization
classes: wide
---

# Background

When I was doing visualization for taxi trips dataset, I realize that a calendar view is very useful to discover some seasonal insights. It can help us answer questions such as:

* Are there more taxi trips on weekdays or weekends ?
* Are taxi trips generally longer in special days, such Christmas or Thanksgiving.

# Live Demo

Following is the embedded the live example, with worksheets guide step by step.

It's also available [here](https://public.tableau.com/views/calendar_view/CalenderViewExample?:display_count=y&publish=yes&:origin=viz_share_link) on Tabeau Public for a wider view. 

<div class='tableauPlaceholder' id='viz1585640776222' style='position: relative'>
	<noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ca&#47;calendar_view&#47;CalenderViewExample&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'>
		<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
	<param name='embed_code_version' value='3' /> 
	<param name='site_root' value='' />
	<param name='name' value='calendar_view&#47;CalenderViewExample' />
	<param name='tabs' value='yes' />
	<param name='toolbar' value='yes' />
	<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ca&#47;calendar_view&#47;CalenderViewExample&#47;1.png' /> 
	<param name='animate_transition' value='yes' />
	<param name='display_static_image' value='yes' />
	<param name='display_spinner' value='yes' />
	<param name='display_overlay' value='yes' />
	<param name='display_count' value='yes' />
	<param name='filter' value='publish=yes' /></object>
</div>
<script type='text/javascript'>                    
	var divElement = document.getElementById('viz1585640776222');                    
	var vizElement = divElement.getElementsByTagName('object')[0];                   
	if ( divElement.offsetWidth > 800 ) { 
		vizElement.style.minWidth='650px';
	vizElement.style.maxWidth='100%';
	vizElement.style.minHeight='450px';
	vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { 
		vizElement.style.minWidth='650px';
	vizElement.style.maxWidth='100%';
	vizElement.style.minHeight='450px';
	vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else { 
		vizElement.style.width='100%';
	vizElement.style.minHeight='750px';
	vizElement.style.maxHeight=(divElement.offsetWidth*1.77)+'px';}     
	var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
	vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
