---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: sigcse2021-header.jpg
widget1:
  title: "COVID-19 Plans"
  # url: '#'
  image: covid-widget.png
  text: 'The SIGCSE Board and Leadership Team are considering various options for SIGCSE 2021.  More info will be posted soon!'
widget2:
  title: "Submit to SIGCSE!"
  url: 'http://sigcse2021.sigcse.org/SIGCSE2021CFP.pdf'
  text: 'See the Call for Papers for more information on submitting to SIGCSE 2021!'
  image: ribbons-widget.png
widget3:
  title: "More Info Soon!"
  image: widget-github-303x182.jpg
  text: 'We are currently working on the website!  Please come back soon for more information about SIGCSE!'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: 
  text: Submit to SIGCSE 2021 ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>