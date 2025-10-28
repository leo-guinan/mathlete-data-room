---
title: How to Solve the Travelling Salesperson Problem
---

<!DOCTYPE html>
<html><head><meta content="text/html; charset=utf-8" http-equiv="Content-Type"/><title>How to Solve the Travelling Salesperson Problem</title><style>
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
<h1 class="p-name">How to Solve the Travelling Salesperson Problem</h1>
</header>
<section class="p-summary" data-field="subtitle">
It Actually Isn’t That Hard.
</section>
<section class="e-content" data-field="body">
<section class="section section--body section--first section--last" name="07d5"><div class="section-divider"><hr class="section-divider"/></div><div class="section-content"><div class="section-inner sectionLayout--insetColumn"><h3 class="graf graf--h3 graf--leading graf--title" id="3593" name="3593">How to Solve the Travelling Salesperson Problem</h3><h4 class="graf graf--h4 graf-after--h3 graf--subtitle" id="fc66" name="fc66">It Actually Isn’t That Hard.</h4><figure class="graf graf--figure graf-after--h4" id="c1c5" name="c1c5"><img class="graf-image" data-height="1191" data-image-id="1*RVtq6XpX4W2nJeFj8jcgfQ.png" data-is-featured="true" data-width="1280" src="https://cdn-images-1.medium.com/max/800/1*RVtq6XpX4W2nJeFj8jcgfQ.png"/><figcaption class="imageCaption">By Xypron — Own work, Public Domain, <a class="markup--anchor markup--figure-anchor" data-href="https://commons.wikimedia.org/w/index.php?curid=10645665" href="https://commons.wikimedia.org/w/index.php?curid=10645665" rel="nofollow noopener" target="_blank">https://commons.wikimedia.org/w/index.php?curid=10645665</a></figcaption></figure><p class="graf graf--p graf-after--figure" id="0b93" name="0b93">Let’s examine the Travelling Salesperson Problem.</p><blockquote class="graf graf--pullquote graf-after--p" id="0762" name="0762">The <strong class="markup--strong markup--pullquote-strong">travelling salesman problem </strong>(also called the <strong class="markup--strong markup--pullquote-strong">travelling salesperson problem</strong><a class="markup--anchor markup--pullquote-anchor" data-href="https://en.wikipedia.org/wiki/Travelling_salesman_problem#cite_note-1" href="https://en.wikipedia.org/wiki/Travelling_salesman_problem#cite_note-1" rel="noopener" target="_blank">[1]</a> or <strong class="markup--strong markup--pullquote-strong">TSP</strong>) asks the following question: “Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?” It is an <a class="markup--anchor markup--pullquote-anchor" data-href="https://en.wikipedia.org/wiki/NP-hardness" href="https://en.wikipedia.org/wiki/NP-hardness" rel="noopener" target="_blank" title="NP-hardness">NP-hard</a> problem in <a class="markup--anchor markup--pullquote-anchor" data-href="https://en.wikipedia.org/wiki/Combinatorial_optimization" href="https://en.wikipedia.org/wiki/Combinatorial_optimization" rel="noopener" target="_blank" title="Combinatorial optimization">combinatorial optimization</a>, important in <a class="markup--anchor markup--pullquote-anchor" data-href="https://en.wikipedia.org/wiki/Theoretical_computer_science" href="https://en.wikipedia.org/wiki/Theoretical_computer_science" rel="noopener" target="_blank" title="Theoretical computer science">theoretical computer science</a> and <a class="markup--anchor markup--pullquote-anchor" data-href="https://en.wikipedia.org/wiki/Operations_research" href="https://en.wikipedia.org/wiki/Operations_research" rel="noopener" target="_blank" title="Operations research">operations research</a>.</blockquote><p class="graf graf--p graf-after--pullquote" id="8e19" name="8e19">Link: <a class="markup--anchor markup--p-anchor" data-href="https://en.wikipedia.org/wiki/Travelling_salesman_problem" href="https://en.wikipedia.org/wiki/Travelling_salesman_problem" rel="nofollow noopener noopener" target="_blank">https://en.wikipedia.org/wiki/Travelling_salesman_problem</a></p><p class="graf graf--p graf-after--p" id="47e7" name="47e7">Perfectly clear, right? The problem is that the salesperson in the problem can’t figure out the optimum route given all of the data at the start. But what does the problem lack? Three things:</p><ul class="postList"><li class="graf graf--li graf-after--p" id="ce8a" name="ce8a">Time</li><li class="graf graf--li graf-after--li" id="c401" name="c401">Learning</li><li class="graf graf--li graf-after--li" id="3cda" name="3cda">Communication</li></ul><p class="graf graf--p graf-after--li" id="5060" name="5060">These are the components of being human. The -person part of traveling salesperson. Let’s add the -person back in. Let’s say that there is more than one traveling salesperson, each starting at a given node. Each finds the optimal routes that are close to them. Then suboptimal routes after that, the further from their starting point. But each can learn more efficient routes in time. And each of the salespeople will share their information with each other. Each local optimal solution will be put back into the global collection of solutions. Then each of the salespeople can learn from the global collection. People multiply over time. They learn. They communicate.</p><p class="graf graf--p graf-after--p graf--trailing" id="549f" name="549f">We need to understand that computers and humans are the same in some ways. Different in others. But humans evolved to solve problems. In order to solve the hard problems, we need to focus on combining the strengths of humans and computers. A symbiotic relationship is much better than the alternative.</p></div></div></section>
</section>
<footer><p>By <a class="p-author h-card" href="https://medium.com/@guinanleo">Leo Guinan</a> on <a href="https://medium.com/p/fa982146d9ac"><time class="dt-published" datetime="2020-09-27T16:38:08.061Z">September 27, 2020</time></a>.</p><p><a class="p-canonical" href="https://medium.com/@guinanleo/how-to-solve-the-travelling-salesperson-problem-fa982146d9ac">Canonical link</a></p><p>Exported from <a href="https://medium.com">Medium</a> on October 11, 2025.</p></footer></article></body></html>