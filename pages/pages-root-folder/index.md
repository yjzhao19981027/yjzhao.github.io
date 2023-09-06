---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth:
title: "JC STEM Lab of MediaML @ HKU"

#slider:
#text_color: white
#shadow_color: black
#slides: 
#  - image: gallery-example-1.jpg
#    slide_html:
#  - image: gallery-example-2.jpg
#    slide_html: "<h2>Yes, this carousel supports html texting</h2>"
#  - image: gallery-example-3.jpg
#    slide_html: "<h2>Yes, this carousel supports html texting</h2>"

sidebar: right

widget1:
  title: "GradNet ICCV2019 Demo"
  url: 'https://youtu.be/tWDbs3VrnbU'
  video: '<iframe width="360" height="240" src="https://www.youtube.com/embed/tWDbs3VrnbU" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width: 100%; max-height: 150pt;"></iframe>'
  text: 'Check out our demo for Visual Object Tracking'
widget2:
  title: "Video Tracking"
  url: 'https://www.youtube.com/watch?v=M1LqUV4jLbM'
  text: 'Implementation of MDNet, KCF and SiamFC.'
  video: '<iframe src="https://www.youtube.com/embed/M1LqUV4jLbM" width="360" height="240" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width: 100%; max-height: 150pt;"></iframe>'
widget3:
  title: "Pose Tracking"
  url: 'https://youtu.be/CiKJuAH2U8I'
  video: '<iframe src="https://www.youtube.com/embed/AL-8XCzRFo0" width="360" height="240" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width: 100%; max-height: 150pt;"></iframe>'
  text: 'Our team won the 2nd place in the pose-track challenge.'

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




---

<div class="pc" style="margin-left: 2%">
<b>JC STEM Lab of MediaML</b> @ HKU is founded in 2022. Our research focuses on endowing machines with the capability to perceive, understand, reconstruct, and interact with the visual world, with the following focuses:
    <ul style="margin-bottom:5px;"> 
      <li>label-efficient, transferrable and lifelong machine learning algorithms that are generalizable to various visual tasks</li>
      <li>efficient compression techniques for visual data transmission</li>
      <li>effective techniques for perceiving, interpreting and reasoning multi-modal (including vision, language, etc.) knowledge</li>
      <li>learnable 3D models for extracting 3D semantics, inferring geometrical relationships, and rendering high-fidelity geometrical structures</li>
      <li>deeply learned generative models for synthesizing or translating between multi-modal data.</li>
    </ul>
 The <b>JC STEM Lab of MediaML</b> is run by Prof. Dong Xu (IEEE & IAPR Fellow, Clarivate Analytics 2018 Highly Cited Researcher in the field of Engineering, Receipt of T-MM 2014 Prize Paper Award and CVPR 2010 Best Student Paper Award [with the PhD students supervised by Prof. Xu]) at the University of Hong Kong, Hong Kong.
</div>
