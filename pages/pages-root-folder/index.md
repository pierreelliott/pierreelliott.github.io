---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: site/homepage.jpg
  title: Pierre-Elliott Thiboud
widget1:
  title: "Who am I?"
  url: '/about-me/'
  text: 'Discover who I am with an overview of my studies and achievements.<br/>You can also download my Resume as a PDF document.'
  image: site/about_me.jpg
widget2:
  title: "Portfolio"
  url: '/portfolio/'
  image: site/portfolio.jpg
  text: 'Every good portfolio website has a ... well, a portfolio.'
widget3:
  title: "View my creations on GitHub"
  url: 'https://github.com/pierreelliott'
  image: site/code.jpg
  text: "While most of my repositories aren't licensed (I need to do it... sometime) you might find interesting to see how I managed to achieve a thing or two."
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
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
show_blog: true
---

<!--
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
-->
