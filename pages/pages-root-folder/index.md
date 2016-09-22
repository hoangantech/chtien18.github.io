---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Tổng hợp tài liệu học tập"
  url: 'http://chtien.xyz/docs'
  image: widget-datsach.jpg
  text: 'Tập hợp tài liệu tự học: lập trình web, lập trình Arduino, Raspberry Pi, công nghệ Internet of Things - IoT'

widget2:
  title: "Mục Sinh viên"
  url: 'http://chtien.xyz/'
  image: widget-phanbon.png
  text: 'Các tin tức liên quan đến học tập, sinh viên,....'
#  video: '<a href="#" data-reveal-id="videoModal"><img src="/images/" width="302" height="182" alt=""/></a>'
widget3:
  title: "Có thể bạn quan tâm"
  url: ''
  image: widget-tinhdausa.jpg
  text: ''
  
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
  url: https://tinyletter.com/rauthuycanhcantho
  text: Click nhận tin mới.
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
