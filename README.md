# odin-landing-page
## Introduction

This one seems like a bit of a challenge. Taking a completed design and transforming it to a 
completed webpage isn't something I've had to do up until this point, but it's a vital part of 
web development. Thus, I'll try and break down my thought process for building the website in here 
in hopes that it might be helpful to someone looking at this in the future.

---
## Design Specs
The provided design lists five main sections as well as a footer. In this instance, the header is included in the first section. The breakdown is as follows:

1. Header & Hero
2. Gallery
3. Quote
4. Call to Action
5. Footer

Each section alternates background colors from dark blue to white to grey and then reverse. In addition, there appears to be a margin on both the left and right sides of the page, pushing in the content.

In order to make this work, we need a few things to be put into place before anything else. 

1. We need a *container* wrapping the entire website to achieve the 'stacking' effect seen in the design

2. We need *sections* that define the height of each section

3. We need a secondary *container* on which to apply the margins. Without this, the background colors would not reach the edges of the page.