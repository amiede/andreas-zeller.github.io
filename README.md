# About Me

I do software research.  My students and I create tools and techniques that **help developers build better software** - by automatically testing, analyzing, and debugging its code and its development process.

Our approaches have had quite some impact in theory and practice.  My [Curriculum Vitae](assets/ZellerCV.pdf) lists the most important achievements.


## Latest News from [@AndreasZeller](https://twitter.com/AndreasZeller)

<a class="twitter-timeline" data-lang="en" data-height="300" data-width="350" data-chrome="noheader nofooter noborders transparent"
href="https://twitter.com/AndreasZeller">Tweets by AndreasZeller</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 


## Current Projects

Our research projects involve generating software tests, automated debugging and repair, analyzing mobile systems, analyzing user interfaces, and more - see our [latest publications](https://scholar.google.com/citations?user=-Qytr_YAAAAJ&hl=en&oi=ao) for details.  Our techniques typically apply and combine several techniques including dynamic analysis, static analysis, specification mining, test generation, natural language processing, machine learning, and formal languages.

My largest project these days is [The Fuzzing Book](https://www.fuzzingbook.org/) - an interactive testbook on test generation ("fuzzing") techniques.  You can execute and edit the code right in your browser.


## Current Courses

In Summer 2020, we will offer a seminar on advanced testing and debugging.  Details to follow soon!


## My Group

At CISPA and Saarland University, I work with [great students and Post-Docs from across the world](Group.md) on cutting-edge research.

We are constantly looking out for great students and Postdocs.  Our positions are well paid and allow for highly productive research.  If you're interested in a PhD or Postdoc position, please [apply at CISPA](https://www.cispa.saarland/).


## Theses

If you are a student of Saarland University and have fun with automated program analysis, testing, and debugging, you might want to do a thesis with us.  [Here are the details on how this works.](Theses.md)


## My Blog

My [blog](Blog.md) has a mixture of various topics from academia and software development, often with a humorous touch.  Here is a selection of popular posts:

<ul>
  {% for post in site.posts %}
  {% if post.tags contains "popular" %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      (<span class="date">{{ post.date | date: "%Y-%m-%d" }}</span>)
    </li>
  {% endif %}
  {% endfor %}
</ul>

<!-- [All blog posts](Blog.md) -->


## Stay Tuned

All relevant events regarding our work are [posted on Twitter](https://twitter.com/AndreasZeller).

<a href="https://twitter.com/AndreasZeller?ref_src=twsrc%5Etfw" class="twitter-follow-button">Follow @AndreasZeller</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
