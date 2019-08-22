What would TRL for software look like?

I saw this interesting tweet a while ago, and I haven’t been able to stop thinking about it. (embed the tweet here - https://twitter.com/tectonic/status/1158478812801224704?s=21 and use https://keitaito.com/blog/2017/01/20/embedding-tweets-in-github-pages.html to embed it )

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">The software industry needs an equivalent of NASA’s TRL metric. https://esto.nasa.gov/files/trl_definitions.pdf <a href="https://twitter.com/tectonic/status/1158478812801224704?s=20">https://twitter.com/tectonic/status/1158478812801224704?s=20</a></p>&mdash; Andrew Cantino (@tectonic) <a href="https://twitter.com/tectonic/status/1158478812801224704?s=20">August 5, 2019</a></blockquote>
<script async="" src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Check out my iOS game, High5! <a href="https://t.co/QZEKLg3G2i">https://t.co/QZEKLg3G2i</a></p>&mdash; Keita Ito (@keitaitok) <a href="https://twitter.com/keitaitok/status/504110217940836353">August 26, 2014</a></blockquote>

  <p class="TweetTextSize TweetTextSize--jumbo js-tweet-text tweet-text" lang="en" data-aria-label-part="0">The software industry needs an equivalent of NASA’s TRL metric. <a href="https://t.co/Ldp3cbDUBW" rel="nofollow noopener" dir="ltr" data-expanded-url="https://esto.nasa.gov/files/trl_definitions.pdf" class="twitter-timeline-link" target="_blank" title="https://esto.nasa.gov/files/trl_definitions.pdf" ><span class="tco-ellipsis"></span><span class="invisible">https://</span><span class="js-display-url">esto.nasa.gov/files/trl_defi</span><span class="invisible">nitions.pdf</span><span class="tco-ellipsis"><span class="invisible">&nbsp;</span>…</span></a></p>


What would Technology Readiness Levels (TRLs) in the software world look like? 

First, what is a TRL? It is a metric used by NASA to assess how well-developed a technology is. Mr. Cantino provides a <a href="https://esto.nasa.gov/files/trl_definitions.pdf">handy definition chart </a> from NASA that explains really clearly what these things are. 

The system works well for NASA, and for the Department of Defense (which uses a slightly different system). However, I do not think that the metric works particularly well for software outside of these two organizations (and supporting contractors), because the metric does not consider the cyclical nature of software development, as opposed to hardware products which are more frequently either one-offs, or several copies of the same design with no incremental improvement. 

NASA product development tends to take longer than commercial software development, which is more likely to be managed according to agile development principles. These principles enable products to succeed, or fail, much more quickly. While TRLs could work for software (which is a technology), it should be possible to create a more precise metric to assess the readiness of software, given how much more limited in scope “software” is than “technology.”

Here is my vision for what Software Readiness Levels might look like. [present chart as table below]
TRL/SRL | NASA | Commercial Software 
1 | basic principle reported | software need identified 
2 | tech concept or application formulated | data processing, control flow paths determined
3 | proof of concept in lab | software product developed to point where code review is viable 
4 | component validation in lab environment | unit testing
5 | component validation in relevant environment | integration testing
6 | system validation in relevant environment | feature acceptance testing
7 | prototype demo in space | software release to development environment
8 | flight qualification through test and demo | software release to operational environment
9 | flight proven through successful ops | software performed nominally in operational context AND incremental update/maintenance release is at software TRL 1 (software is a cyclical process, code good enough that can be modified for next version instead of tossed)

What is the difference between TRLs and Software Readiness Levels (SRLs)?

SRL 1 is that a need for a product has been identified. This is as opposed to TRL 1, which is the reporting of a principle, because software development in the commercial sector seems to me to much more commonly apply existing technological frameworks in new contexts than introduce new contexts. So the TRL 1 definition does not work. What should replace it? In agile decelopment, everything is driven by the user’s needs, so it seems...logical...that the identification of a need is the first step in the readiness of a software product.

SRL 2 is like TRL 2 in that both of them define what will be created later in the development pipeline. SRL 2, defined by understanding a product’s control flow and data processing path, is actually slightly more advanced than TRL 2, which seems to require ideation of an use for the technology.

SRL 3 and TRL 3 are probably the most similar of the reference levels, as this point in both systems is the minimum work that needs to be done for a concept to be validated or rejected based on the technologies being used, in an environment as favorable to development as possible.

SRL 4, SRL 5, and SRL 6 are roughly comparable to TRL 4, TRL5, and TRL 6, respectively. At this stage, a technology or a software product is undergoing tests of increasing rigor to ensure its ability to operate successfully. Somewhere in these SRLs is probably the “code freeze”, after which changes to the product are pushed to the next release.

SRL 7 and SRL 8 correspond roughly to TRL 7 and TRL 8, respectively. This is the point where products start deploying. A prototype in space strikes me as corresponding roughly to a software deployment in a development environment. Similarly, a software product’s initial deployment in an operational environment performs essentially the same role as flight qualifying hardware through a demonstration. (insert graphic of “it worked in dev”)

SRL 9, that a product is considered totally operational, varies from NASA’s definition of TRL 9. NASA demands successful operations. So does software, but that’s actually not enough. For software to be really operational, development progress must begin on a maintenance or upgrade product update. Why is this? First, this is the ultimate proof that a software product is “good enough” to peers and stakeholders - it is not being thrown out when new features are needed, but it is being built upon and expanded. Second, this emphasizes the cyclical nature of software development, as opposed to technology maturation. A software development cycle really ends at the beginning of the cycle to update or replace it, as opposed to a technology maturation process, which develops the technology, but is not inherrently cyclical. If the technology is improved, the cycle can be repeated, but it does not seem to be an intrinsic part of the maturation process.

So what?

Through thinking about this tweet, and writing this blog post, I’ve had to think through the development process, and attempt to discretize what can be a very fluid thing into defined steps. I think that’s helped me better understand what the process actually is.
