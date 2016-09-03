---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_leaf.jpg
widget1:
  title: "Services"
  url: 'http://stonetreefarms.github.io/about/services/'
  image: riding.jpg
  text: 'At Stonetree Farms we pride ourselves on the quality of our services. Whether you are boarding a horse, taking lessons, using our coaching/show services or attending a clinic, you are sure to have a positive and favorable experience.'
widget2:
  title: "Horses"
  url: 'http://stonetreefarms.github.io/horses/'
  image: horse.jpg
  text: 'We offer a variety of horses and ponies for sale to suit your needs and price ranges. We can also help you find a suitable mount out-of-barn, and may have other horses or ponies available in the barn for sale, lease, or part board.'
widget3:
  title: "Camp"
  url: 'http://stonetreefarms.github.io/camp/'
  image: jump.jpg
  text: 'We have an affordable riding camp for a vast variety of ages and riding levels over any school break. Stonetree Camp offers two daily riding lessons, (or a lesson and a games period) where <strong>skills</strong>, <strong>horsemanship</strong>, and <strong>fun</strong> will be focused on!'
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
  url: https://stonetreefarms.github.io/camp/
  text: Sign me up for camp! ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
