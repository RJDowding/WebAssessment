# WebAssessment

Reece Dowding 52211215

In the design of the website I decided to opt for a modern and minimalist design. This enables for a consistent experience and modular programming.

In terms of design I chose a consistent design across the website. Colours, images, navigation and other experience elements are the same across the pages and behave the same throughout. These elements include the navbar, banner and headers. Because such elements are fundamental to navigation and experience, I believe consistency is important. 

I decided to implement a specific font — Lato to provide a more pleasing experience. It's used throughout the website, with small changes depending if the usage is for banners, headers or paragraphs. Small changes were made in text spacing, weight and lightness. 
I implemented images as bordered circular elements, some of which behave as hyperlinks with an animation signifying to the user of the link. To the right if the images is text which further provide context to the images.

All animations were completed in pure css, there are small animations throughout the website, hyperlinks and elements within the banner/header. 
Regarding challenges, I found it difficult to ensure compatibility across devices. I'd program the website across several devices and at times some elements would work as intended on one device but not another, mainly due to element positioning. In mitigation of this I decided to use padding percentage of screen space, rather than fixed element positioning, which has seemed to resolve the issues.

I've also had issues with text, specifically changing text to fit around other elements on screen. An example of this is how text or <p> isn’t designed to be used alongside images. But if you make css changes to the <p> tag, it changes the positioning of all p elements across the website. Which isn’t suitable as the positioning of text on one webpage isn’t the same as the other. 
  
Hence I decided to use custom elements for text depending what is happening onscreen. I created an element specifically for text next to an image to ensure consistent aesthetic. I also created other elements for text without images.
