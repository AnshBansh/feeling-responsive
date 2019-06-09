---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: main2.jpg
  caption: I Help People Become Financially Free. DO YOU HAVE WHAT IT TAKES?
  caption_url: http://anshulbansal.com/
  
widget1:
  title: "Blogs & More"
  url: 'http://www.anshulbansal.com/blog/'
  image: widget-1-302x182.jpg
  text: 'Daily healthy diet for your mind. <em>Anshul Bansal</em> team offers you insightful 
  collection of thoughts and ideas from around the world. We Help People Become Financially Free. 
  Learn about money and more'
widget2:
  title: "WANT TO BECOME FINANCIALLY INDEPENDENT? JOIN OUR FREE TRAINING."
  url: 'https://github.com/AnshBansh/feeling-responsive'
  text: '1. Learn how to make free websites and earn 100$ per day,  <em>The Easy Way.</em>
<br/>2. Absolutely Free hosting. No need to pay for expensive hosting services.
<br/>3. Learn Facebook Ads and marketing to grow your business exponentially. 
<br/>4. Make your blogs viral and earn through affiliate marketing and google ads.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://www.anshulbansal.com/images/learngrow.jpg"
   width="302" height="182" alt=""/></a>'

widget3:
  title: "Portfolio and testimonials"
  url: 'https://github.com/AnshBansh/feeling-responsive'
  image: portfolio.jpeg
  text: 'Our work and progress'
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
  url: https://tinyletter.com/anshulbansal
  text: Inform me about new updates and features ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVv" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
