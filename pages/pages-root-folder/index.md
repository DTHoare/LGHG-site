---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
    title: "London GHG"
    subtitle: "Greenhouse Gas Sensor Network for London"
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
  text: 'An overview of the two most important greenhouse gases: Carbon Dioxide and Methane.'
widget3:
  title: "Instruments"
  url: '/instruments'
  image: instrument.png
  text: 'An insight into the equipment used to measure greenhouse gases.'
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
