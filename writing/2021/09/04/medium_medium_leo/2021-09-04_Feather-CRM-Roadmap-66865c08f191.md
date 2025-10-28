---
title: Feather CRM Roadmap
---

<!DOCTYPE html>
<html><head><meta content="text/html; charset=utf-8" http-equiv="Content-Type"/><title>Feather CRM Roadmap</title><style>
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
<h1 class="p-name">Feather CRM Roadmap</h1>
</header>
<section class="p-summary" data-field="subtitle">
Where have we been and where are we going?
</section>
<section class="e-content" data-field="body">
<section class="section section--body section--first" name="aabc"><div class="section-divider"><hr class="section-divider"/></div><div class="section-content"><div class="section-inner sectionLayout--insetColumn"><h3 class="graf graf--h3 graf--leading graf--title" id="6b95" name="6b95">Feather CRM Roadmap</h3><h4 class="graf graf--h4 graf-after--h3 graf--subtitle" id="1809" name="1809">Where have we been and where are we going?</h4><h3 class="graf graf--h3 graf-after--h4" id="aece" name="aece">Current Status</h3><p class="graf graf--p graf-after--h3" id="1191" name="1191">Feather has gone through a couple of iterations since I initially published this roadmap. Now that I’ve talked with a bunch of users and thought about what problems Feather is really solving, I decided it was time to update the roadmap.</p><h4 class="graf graf--h4 graf-after--p" id="8dcb" name="8dcb">The Problems</h4><p class="graf graf--p graf-after--h4" id="f9b7" name="f9b7">There are several problems being solved at the heart of Feather.</p><ol class="postList"><li class="graf graf--li graf-after--p" id="c4c3" name="c4c3">Most people do not build strong relationships online. They focus on the metrics presented: likes, retweets, following, etc.</li><li class="graf graf--li graf-after--li" id="9fe0" name="9fe0">Most people do not use Twitter intentionally. But the most successful people do.</li><li class="graf graf--li graf-after--li" id="8c35" name="8c35">There is a lot of noise in the normal user’s Twitter feed, so they end up mindlessly scrolling to try to find the signal.</li></ol><h4 class="graf graf--h4 graf-after--li" id="d166" name="d166">The Solution</h4><ol class="postList"><li class="graf graf--li graf-after--h4" id="c098" name="c098">Start with personal relationships.</li><li class="graf graf--li graf-after--li" id="1345" name="1345">Give people tools that help them accomplish their goals intentionally. Make them figure out their goals.</li><li class="graf graf--li graf-after--li" id="d797" name="d797">Provide filters that users can easily use to make sure they get mostly signal.</li></ol><h4 class="graf graf--h4 graf-after--li" id="1160" name="1160">The Assumptions</h4><p class="graf graf--p graf-after--h4" id="c1b5" name="c1b5">I’ve made several assumptions that I’m basing everything on.</p><ol class="postList"><li class="graf graf--li graf-after--p" id="2fd2" name="2fd2">People are overwhelmed by their Twitter feed.</li><li class="graf graf--li graf-after--li" id="c8c4" name="c8c4">The right 10 relationships are better than 10,000 random ones.</li><li class="graf graf--li graf-after--li" id="7686" name="7686">The idea that we have to keep retweeting and re-sharing content is inefficient and unneeded in an efficient system.</li><li class="graf graf--li graf-after--li" id="190c" name="190c">There are better ways to get your content into the hands of your audience than have been previously created.</li><li class="graf graf--li graf-after--li" id="57fa" name="57fa">Email is an incredibly useful and drastically overused tool.</li><li class="graf graf--li graf-after--li" id="7660" name="7660">Most newsletters are just a reason to recycle existing content to readers. Again, this seems quite inefficient.</li><li class="graf graf--li graf-after--li" id="07dc" name="07dc">With new platforms being created every day, it’s important to maintain relationships outside of the individual platforms.</li><li class="graf graf--li graf-after--li" id="c6f5" name="c6f5">There exists a minimum viable audience at which point content that gets released will find its way to a majority of the audience.</li><li class="graf graf--li graf-after--li" id="41b5" name="41b5">Every platform is competing to keep users on their platform instead of focusing on a specific type of content. This results in a bunch of companies competing with each other in inefficient manners. This is why we have Twitter threads instead of blogs, Twitter spaces instead of podcasts/clubhouse, etc.</li><li class="graf graf--li graf-after--li" id="f3a7" name="f3a7">The amount of content produced needs strong filtering otherwise consumers will be overwhelmed.</li></ol><h4 class="graf graf--h4 graf-after--li" id="fb25" name="fb25">Current State of the App</h4><p class="graf graf--p graf-after--h4" id="f53b" name="f53b">I’ve started building out a lot of the filters I need in order to make sure I’m building stronger relationships. Since I’ve started using it personally, I’ve found that I’m forming better relationships with people on Twitter.</p><p class="graf graf--p graf-after--p" id="4fab" name="4fab">I started by building out personal subscriptions. With this tool, you can get a weekly email with all of a user’s tweets, excluding replies and retweets. I found that I was missing up to 75% of peoples’ tweets, even the people I was actively trying to keep up with. With Feather, I no longer miss those tweets. And since I was able to see those tweets and respond to them, my engagement numbers ended up going up.</p><p class="graf graf--p graf-after--p" id="ea78" name="ea78">After 2 weeks of using Feather personally, this is what my Twitter analytics looked like:</p><figure class="graf graf--figure graf-after--p" id="237c" name="237c"><img class="graf-image" data-height="518" data-image-id="1*q9nXX1-vKsUhmpphGbt3kQ.png" data-width="2440" src="https://cdn-images-1.medium.com/max/800/1*q9nXX1-vKsUhmpphGbt3kQ.png"/><figcaption class="imageCaption">Stats from the Author’s Twitter Account</figcaption></figure><p class="graf graf--p graf-after--figure" id="9553" name="9553">That’s impressive enough to plan a launch. I think there is definitely something useful here, I just need to try to get others to see if they can replicate the success.</p><p class="graf graf--p graf-after--p" id="0349" name="0349">For personal subscriptions, I’m currently examining two different models:</p><ul class="postList"><li class="graf graf--li graf-after--p" id="fe03" name="fe03">The individual — This is someone who is on social media to make friends or just connect with people. They are not interested in building an audience. People will be able to subscribe to these accounts on a limited basis, with the ability to access more via a paid plan.</li><li class="graf graf--li graf-after--li" id="a77d" name="a77d">The Creator — This is someone who is actively trying to grow an audience. They likely have an email list or are considering building one. Right now, the plan is to have a creator account that will give creators the ability to let people subscribe to them. I’m thinking about letting users get a certain number of subscriptions before requiring them to upgrade their accounts.</li></ul><p class="graf graf--p graf-after--li" id="5386" name="5386">These two models will be the focus of my launch on February 1.</p><h3 class="graf graf--h3 graf-after--p" id="9095" name="9095">Upcoming Features</h3><p class="graf graf--p graf-after--h3" id="0ca6" name="0ca6">These features will be dependant on feedback I get from the launch, but here’s the current plan for the rest of Q1 and beyond:</p><h4 class="graf graf--h4 graf-after--p" id="c5f2" name="c5f2">Individual</h4><ul class="postList"><li class="graf graf--li graf-after--h4" id="be38" name="be38">For this group of users, there will be tools added for saving content from their favorite creators and ways for them to connect more closely.</li></ul><h4 class="graf graf--h4 graf-after--li" id="3a2a" name="3a2a">Creator</h4><ul class="postList"><li class="graf graf--li graf-after--h4" id="4b7f" name="4b7f">I’ve got a number of tools planned for the creator group of users. These will include tools for content cataloguing, distribution, audience management, and more.</li></ul><h4 class="graf graf--h4 graf-after--li" id="9c93" name="9c93">Community</h4><ul class="postList"><li class="graf graf--li graf-after--h4" id="9f70" name="9f70">I’ve got some tools in the works for communities to help members connect and for the communities to elevate member content.</li></ul><h4 class="graf graf--h4 graf-after--li" id="0467" name="0467">Professional</h4><ul class="postList"><li class="graf graf--li graf-after--h4 graf--trailing" id="fe68" name="fe68">Tools for this group include enhanced DM management, tools for moving people through workflows, and scheduling tools for connecting with people.</li></ul></div></div></section><section class="section section--body section--last" name="9e28"><div class="section-divider"><hr class="section-divider"/></div><div class="section-content"><div class="section-inner sectionLayout--insetColumn"><p class="graf graf--p graf--leading graf--trailing" id="11ec" name="11ec"><a class="markup--anchor markup--p-anchor" data-href="https://www.feathercrm.io/profile/leo" href="https://www.feathercrm.io/profile/leo" rel="noopener" target="_blank"><em class="markup--em markup--p-em">To keep up to date on my latest projects, check out my profile on Feather and sign up to receive my tweets via email on a weekly basis. This is the best way to follow what I’m up to and really see the work in action. It’s not polished like an email newsletter, but there’s a lot of gems in there that you might find interesting.</em></a></p></div></div></section>
</section>
<footer><p>By <a class="p-author h-card" href="https://medium.com/@guinanleo">Leo Guinan</a> on <a href="https://medium.com/p/66865c08f191"><time class="dt-published" datetime="2021-09-04T23:00:17.431Z">September 4, 2021</time></a>.</p><p><a class="p-canonical" href="https://medium.com/@guinanleo/feather-crm-roadmap-66865c08f191">Canonical link</a></p><p>Exported from <a href="https://medium.com">Medium</a> on October 11, 2025.</p></footer></article></body></html>