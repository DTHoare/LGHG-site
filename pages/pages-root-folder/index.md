---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
    title: London Greenhouse Gas Monitoring Network
    background-color: "#c7e8e8"
    image: london.png
#header:
#  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "About"
  url: '/about'
  image: london.png
  text: 'What is the London Greenhouse Gas Measurement Network?'
widget2:
  title: "Greenhouse Gases"
  url: '/greenhouse-gases'
  image: methane.png
  text: 'An overview of the science.'
widget3:
  title: "Instruments"
  url: '/instruments'
  image: instrument.png
  text: 'LGHG is a collobaration between public and academic partners.'
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
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
