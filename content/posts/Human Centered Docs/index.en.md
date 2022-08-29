---
title: "Human- Centered Documentation for Web Developers"
date: 2022-08-16T11:38:15-04:00
lastmod: 2022-08-16T11:38:15-04:00
draft: false
author: "Africa Kenyah"
authorLink: "https://www.africakenyah.com"
description: "Accessibility Considerations for Technical Documentation"
images: ["featured-image.png"]
resources:
- name: "featured-image"
  src: "featured-image.png"

tags: ["accessibility", "technical documentation"]
categories: ["web accessibility"]

hiddenFromHomePage: false

toc:
  enable: false
---

This article was originally created for a Twitter space with fellow web developer [Lucia](https://twitter.com/CerchieLucia). We covered topics including actionable first steps for better readability and usability of technical documentation. This article includes extra information and context not discussed during our chat.

{{< tweet 1559619705870159874 >}}

Note that twitter spaces only work on mobile for the time being.

# Considerations for Accessible Technical Documentation

![Drawing of women's profile with long black hair with a worried look on face and lightbulb over head](https://cdn.hashnode.com/res/hashnode/image/upload/v1660688669253/fWyDdKNvZ.webp)
## What is human-centered design and how can we use it as developers?
Human-centered design is a framework that centers the user's needs. It evaluates the requirements of the user and what is needed to complete tasks. This increases accessibility by focusing on understanding the needs of the person using your product/ material. 

There are 4 Principles to this process:
1. Understanding the context of the use
2. Specifying user requirements
3. Producing design solutions
4. Evaluating the design<br><br>
[Source: NIST (National Institute of Standards and Technology)](https://www.nist.gov/itl/iad/visualization-and-usability-group/human-factors-human-centered-design)

If you'd like to dive deeper into the principles of human-centered design [check out this video](https://www.youtube.com/watch?v=rmM0kRf8Dbk) by Don Norman.

## Who is reading our documentation?
For web developers, other developers are usually our target audience. In some cases, designers, product owners, managers, and end users may also use our documentation.

## Who is impacted the most by documentation that does not consider accessibility?
15% of the world has some form of disability according to the World Health Organization. Many more do not self-report. It may be fair to assume that up to 20% of the people who use your documentation may use alternative supports or strategies to access and understand it.<br><br>

### Individuals impacted by poor accessibility may include:<br>
<b>Neurodivergent individuals</b> (ADHD, Autism, sensory processing disorders, visual and auditory processing disorders and learning disabilities including dyslexia)<bR>
These individuals work best with:
- Documentation that is written with clear, measurable steps 
- Good use of white space with content broken up into sequential sections
- Consistent use of fonts sizing, types and colors
- Short sentences that do not exceed more than 26 words

<b>Visual, auditory and tactile impairments</b><br>
These individuals work best with documentation that can work well with their assistive technology including: 
- Screen readers*
- Screen Magnifyers
- Specialized keyboards and switches
- Speech to text and text to speech
- High contrast modes<br>

*Screen readers are not only for those with visual impairments but also for those with cognitive and physical impairments.

## Have you ever read documentation that was hard to understand? What made it inaccessible for you? 
<b>Africa's response:</b>
- Documentation where 1 step was really 6 steps, but poorly written so you have to figure out the step in between yourself or from prior knowledge 
- Documentation where there is no structure, just a wall of text
- No bolding or images to break the text up

<b>Lucia's response:</b>
- Technical documentation with a list of features where it isn't written with the user in mind
- Reading a long list of features that doesn't have any organization

## What are some common accessibility mistakes made when writing documentation?

- No alt text or not descriptive enough alt text for images, links, or buttons
- Poor use of semantic HTML
- No headings or headings that do not go in order
- No sequential structure to document 
- Unclear wording, double negatives, long sentences
- Links that are not descriptive ("click here" instead of "GitHub Repo")

## What are my first steps for making my documentation more human-centered and accessible?
### Think about your audience’s needs
In general, they need to be able to:
- Navigate through your documentation to find what they need
- Read and understand the documentation (whether that be visually on the screen or read from a screen reader or other assistive device)
- Interpret images
- Understand what steps to take to complete tasks in the documentation

### Start with semantic HTML
- Look at the structure of your HTML and use native descriptive tags that give information about the elements on the page
- Make sure headings are in the correct order and used for content structure, not styling (always style using CSS)
- Always include alternative text

## What is the first thing you look at when assessing the accessibility of a technical document?
- The <b>structure of the page</b> visually (are things bolded, are the same styles used throughout? )
- Easy to read <b>font styles </b>(Georgia, Helvetica, PT Serif, Open Sans, and Verdana are one of the easiest fonts to read)
- <b>Font size</b> (use rems instead of hardcoding with pixel size so that users who use screen magnifiers can keep their settings for larger text)
- Can the page be <b>magnified x10</b>? 
- <b>Contrast ratios </b>(WCAG 2.0 level AA requires a contrast ratio of at least 4.5:1 for normal text and 3:1 for large text)
- <b>Semantic HTML</b> elements (h1 for the primary purpose of the page, h2 for breaking content into smaller sections, and so on)
- <b>Descriptive alt text</b> for images, links, icons, buttons

## What are some tools to help with increasing human-centered design/ accessibility?
### Chrome accessibility testing extensions:
- [WAVE](https://wave.webaim.org/)  (open source suite of evaluation tools that helps authors make their web content more accessible )
- [Lighthouse](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en)
(open source suite of evaluation tools that helps authors make their web content more accessible ) 
- [Axe by Deque](https://www.deque.com/axe/browser-extensions/) (free automated accessibility testing for your web app)

### Color contrast checkers
- [Web AIM contrast checker](https://webaim.org/resources/contrastchecker/) 
- [Accessible Web Helper](https://chrome.google.com/webstore/detail/accessible-web-helper/gdnpkbipbholkoaggmlblpbmgemddbgb) (chrome extension)
- [Color Contrast Accessibility Validator](https://color.a11y.com/)

### Self-testing
- Can the website be used with only a keyboard? Tab through the page and make sure you can select the navigation areas, headings, paragraphs, buttons, and links without a mouse.
- Can your website be used with a screen reader? Use a screen reader including NVDA (free open sourced screen reader), JAWS (the most used screen user), or VoiceOver (for Mac users)
- Make sure your documentation can be zoomed in 10X 
- Use your website using different web browsers to make sure information is structurally and visually the same
- Proofread or have someone else read your documentation. Can they complete instructions or relay understanding of the information presented?
- Consider having someone who is not an expert at the subject read your documentation. Can they understand the general idea of the page or complete the steps? 

## How can developers present a concept that's both complicated and new in an accessible way?
### Break down steps
- If more than one action is required to complete a step, break down your instructions to include more steps 
- Complete an activity analysis and determine how many actions your documentation requires of the user 
### Use plain language
- Avoid jargon
- Discuss only one topic per paragraph
- Use only the words that are necessary to convey the message
### Use inclusive language
- Avoid using terms like “it's so easy”
- Avoid using gendered language
- Be mindful of using correct language when talking about disabilities


## Final thoughts
While this is not an exhaustive list of things to consider when making documentation human-centered, it is a good start. I hope this is helpful on your journey to be more inclusive of people of all abilities. <br><br>
Do you have any other accessibility tips or considerations not mentioned? Please share them! We would also like to hear from developers impacted by inaccessible documentation and what they have encountered.


