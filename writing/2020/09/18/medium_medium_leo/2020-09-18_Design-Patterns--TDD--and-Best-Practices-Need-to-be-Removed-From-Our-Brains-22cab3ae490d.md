---
title: Design Patterns, TDD, and Best Practices Need to be Removed From Our Brains
---

<!DOCTYPE html>
<html><head><meta content="text/html; charset=utf-8" http-equiv="Content-Type"/><title>Design Patterns, TDD, and Best Practices Need to be Removed From Our Brains</title><style>
      * {
        font-family: Georgia, Cambria, "Times New Roman", Times, serif;
      }
      html, body {
        margin: 0;
        padding: 0;
      }
      h1 {
        font-size: 50px;
        margin-bottom: 17px;
        color: #333;
      }
      h2 {
        font-size: 24px;
        line-height: 1.6;
        margin: 30px 0 0 0;
        margin-bottom: 18px;
        margin-top: 33px;
        color: #333;
      }
      h3 {
        font-size: 30px;
        margin: 10px 0 20px 0;
        color: #333;
      }
      header {
        width: 640px;
        margin: auto;
      }
      section {
        width: 640px;
        margin: auto;
      }
      section p {
        margin-bottom: 27px;
        font-size: 20px;
        line-height: 1.6;
        color: #333;
      }
      section img {
        max-width: 640px;
      }
      footer {
        padding: 0 20px;
        margin: 50px 0;
        text-align: center;
        font-size: 12px;
      }
      .aspectRatioPlaceholder {
        max-width: auto !important;
        max-height: auto !important;
      }
      .aspectRatioPlaceholder-fill {
        padding-bottom: 0 !important;
      }
      header,
      section[data-field=subtitle],
      section[data-field=description] {
        display: none;
      }
      </style></head><body><article class="h-entry">
<header>
<h1 class="p-name">Design Patterns, TDD, and Best Practices Need to be Removed From Our Brains</h1>
</header>
<section class="p-summary" data-field="subtitle">
They are holding us back from our true potential.
</section>
<section class="e-content" data-field="body">
<section class="section section--body section--first" name="555e"><div class="section-divider"><hr class="section-divider"/></div><div class="section-content"><div class="section-inner sectionLayout--insetColumn"><h3 class="graf graf--h3 graf--leading graf--title" id="fb33" name="fb33">Design Patterns, TDD, and Best Practices Need to be Removed From Our Brains</h3><h4 class="graf graf--h4 graf-after--h3 graf--subtitle" id="59fb" name="59fb">They are holding us back from our true potential.</h4><figure class="graf graf--figure graf-after--h4" id="0f6a" name="0f6a"><img alt="Model of a human brain" class="graf-image" data-height="3024" data-image-id="0*x2PgBuK_jaxnjh59" data-is-featured="true" data-unsplash-photo-id="byp5TTxUbL0" data-width="4032" src="https://cdn-images-1.medium.com/max/800/0*x2PgBuK_jaxnjh59"/><figcaption class="imageCaption">Photo by <a class="markup--anchor markup--figure-anchor" data-href="https://unsplash.com/@natcon773?utm_source=medium&amp;utm_medium=referral" href="https://unsplash.com/@natcon773?utm_source=medium&amp;utm_medium=referral" rel="photo-creator noopener" target="_blank">Natasha Connell</a> on <a class="markup--anchor markup--figure-anchor" data-href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral" href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral" rel="photo-source noopener" target="_blank">Unsplash</a></figcaption></figure><p class="graf graf--p graf-after--figure" id="2954" name="2954">I was writing some code the other day, as I do most days. As with most days, I found myself thinking about what I was writing, and how it fits into the overall system architecture. Then I started pondering how we needed a more robust integration testing suite, and let my brain wander a bit. Then I came back to what I was working on, and tried to make the code I was writing fit into the system in the appropriate way. And it was hard.</p><blockquote class="graf graf--blockquote graf-after--p" id="d3f7" name="d3f7">I was doing everything right. But this was still hard.</blockquote><p class="graf graf--p graf-after--blockquote" id="866a" name="866a">I have been a professional programmer for almost a decade. I have studied design patterns. I have a BS in Computer Science, an MS in Software Engineering, and I am working on a second MS in Information Technology. I am fluent in several different programming languages. I love Test-Driven Development (TDD) and have been using it almost exclusively for several years. I was doing everything right. But this was still hard. It wasn’t something that should have been hard, but it was.</p><p class="graf graf--p graf-after--p graf--trailing" id="ed1e" name="ed1e">Why?</p></div></div></section><section class="section section--body" name="08fa"><div class="section-divider"><hr class="section-divider"/></div><div class="section-content"><div class="section-inner sectionLayout--insetColumn"><p class="graf graf--p graf--leading" id="afc7" name="afc7">I started pondering this, and I realized something. There was a time when these concepts were important. They still can be in select situations. But for the most part, we are all doing it wrong. But why is this? Things changed. Things changed a lot.</p><p class="graf graf--p graf-after--p" id="433d" name="433d">I started to look up stats on the number of programmers in the world, and came across a few articles that made some things very clear to me.</p><p class="graf graf--p graf-after--p" id="d5b2" name="d5b2"><strong class="markup--strong markup--p-strong">Article 1: Looking at IT from 1970–2016</strong></p><p class="graf graf--p graf-after--p" id="93fc" name="93fc">Link: <a class="markup--anchor markup--p-anchor" data-href="https://www.census.gov/newsroom/press-releases/2016/cb16-139.html" href="https://www.census.gov/newsroom/press-releases/2016/cb16-139.html" rel="nofollow noopener" target="_blank">https://www.census.gov/newsroom/press-releases/2016/cb16-139.html</a></p><p class="graf graf--p graf-after--p" id="e1d2" name="e1d2">Looking at this, the number of IT workers in the US went from about 500K to 5M over the period of 46 years. That is a 10X increase. That is a huge jump.</p><p class="graf graf--p graf-after--p" id="f6d7" name="f6d7"><strong class="markup--strong markup--p-strong">Article 2: Programmers as part of IT</strong></p><p class="graf graf--p graf-after--p" id="89d6" name="89d6">Link: <a class="markup--anchor markup--p-anchor" data-href="https://www.census.gov/content/dam/Census/library/publications/2016/acs/acs-35.pdf" href="https://www.census.gov/content/dam/Census/library/publications/2016/acs/acs-35.pdf" rel="nofollow noopener" target="_blank">https://www.census.gov/content/dam/Census/library/publications/2016/acs/acs-35.pdf</a></p><p class="graf graf--p graf-after--p" id="7e2f" name="7e2f">According to a quick perusal of this, programmers make up about 25% of the IT workforce. So the number of programmers in 1970 was probably about 125K, up to 1.25M in 2016.</p><p class="graf graf--p graf-after--p" id="4a99" name="4a99"><strong class="markup--strong markup--p-strong">Article 3: The Growth of Software Engineering</strong></p><p class="graf graf--p graf-after--p" id="5714" name="5714">Link: <a class="markup--anchor markup--p-anchor" data-href="https://www.daxx.com/blog/development-trends/number-software-developers-world" href="https://www.daxx.com/blog/development-trends/number-software-developers-world" rel="nofollow noopener" target="_blank">https://www.daxx.com/blog/development-trends/number-software-developers-world</a></p><p class="graf graf--p graf-after--p graf--trailing" id="31c1" name="31c1">This link explores the growth of software engineering both in the US and Worldwide. Spoiler: it is growing fast, and will continue to do so.</p></div></div></section><section class="section section--body" name="57b6"><div class="section-divider"><hr class="section-divider"/></div><div class="section-content"><div class="section-inner sectionLayout--insetColumn"><p class="graf graf--p graf--leading" id="e8a0" name="e8a0">What does any of this have to do with design patterns, TDD, or best practices? Everything.</p><p class="graf graf--p graf-after--p" id="6744" name="6744">These ideas work because everyone understands what they are. Design patterns are great, when they are recognized as such, and followed impeccably. TDD works well if you understand fully what you are doing, and why. Same with best practices.</p><p class="graf graf--p graf-after--p" id="f6a7" name="f6a7">But the workforce is changing rapidly. It is growing rapidly. And many of the people coming into the field may or may not have this knowledge.</p><p class="graf graf--p graf-after--p" id="abac" name="abac">Isn’t that their problem?</p><p class="graf graf--p graf-after--p" id="69de" name="69de">No. It is a problem of the industry. These ideas work well when everyone understands the why behind everything. That was common in the early days of programming, when only a select few would have enough knowledge to actually write software. There needed to be much more formality around the process. These ideas were born of that.</p><p class="graf graf--p graf-after--p graf--trailing" id="c4d4" name="c4d4">But now everyone can be a programmer. I am teaching my kids, ages 5 and 9, to program. People don’t need to know these concepts to be productive. By forcing people to learn these concepts, we are greatly limiting productivity and creativity. Expecting our engineers to understand these before they even get hired is very much a form of gatekeeping. It made sense before. But I don’t think we need that any more.</p></div></div></section><section class="section section--body section--last" name="4618"><div class="section-divider"><hr class="section-divider"/></div><div class="section-content"><div class="section-inner sectionLayout--insetColumn"><figure class="graf graf--figure graf--leading" id="4426" name="4426"><img alt="Person facing away. Back of shirt reads “Burn your problems”" class="graf-image" data-height="4472" data-image-id="0*wmG3Wi-Z_reptDwW" data-unsplash-photo-id="D1QI9bx8KUM" data-width="6708" src="https://cdn-images-1.medium.com/max/800/0*wmG3Wi-Z_reptDwW"/><figcaption class="imageCaption">Photo by <a class="markup--anchor markup--figure-anchor" data-href="https://unsplash.com/@sebastiaanstam?utm_source=medium&amp;utm_medium=referral" href="https://unsplash.com/@sebastiaanstam?utm_source=medium&amp;utm_medium=referral" rel="photo-creator noopener" target="_blank">sebastiaan stam</a> on <a class="markup--anchor markup--figure-anchor" data-href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral" href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral" rel="photo-source noopener" target="_blank">Unsplash</a></figcaption></figure><p class="graf graf--p graf-after--figure" id="9cb7" name="9cb7">Give me a team of people interested in solving a problem. I don’t care if they know anything about programming. I will teach them to program (if they want). But programming isn’t where the problems are solved. They are solved by teams that work together to determine a solution. The implementation details are something to be worked out later. I can learn how to program pretty much anything. You can too, if you want. Google is an amazing tool.</p><p class="graf graf--p graf-after--p graf--trailing" id="6af4" name="6af4">These ideas also tend to box you in to certain ways of thinking. By following these ideas, them being understood or not, you are putting yourself into a rigid mindset. I have rediscovered my productivity by releasing these ideas I have learned over the last decade. The workforce is changing. You can keep your outdated ideas. I want to learn what I can from them, release them, and think of something better.</p></div></div></section>
</section>
<footer><p>By <a class="p-author h-card" href="https://medium.com/@guinanleo">Leo Guinan</a> on <a href="https://medium.com/p/22cab3ae490d"><time class="dt-published" datetime="2020-09-18T16:23:12.034Z">September 18, 2020</time></a>.</p><p><a class="p-canonical" href="https://medium.com/@guinanleo/design-patterns-tdd-and-best-practices-need-to-be-removed-from-our-brains-22cab3ae490d">Canonical link</a></p><p>Exported from <a href="https://medium.com">Medium</a> on October 11, 2025.</p></footer></article></body></html>