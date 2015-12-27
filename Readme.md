# UI Reading List

When I started coding, it was an `index.html` file linked to perhaps `global.css` and `styles.css` all unminified and with an increasing amount of cascade to override previous styles. (`.home #sidebar .some_module h2 {...}`). UI Development today resembles nothing like what it was when I wrote my first tag. This list of articles and talks are ones I return to regularly and repeatedly recommend for anyone doing UI Development today at any level. These apply to traditional server rendered MVC, or cutting edge Single Page Applications. Enjoy!

#### Disclaimer
_These are not meant to be an exhaustive list of everything you need to know, nor a summary of a specific approach to UI Development. Some of these will apply some of the time. But all of them have been helpful with informing my current opinion and skill set._

## The List

Presented in no particular order...

### Videos

* [CSS in JS](https://vimeo.com/116209150) by [Christopher Chedeau](http://blog.vjeux.com/2014/javascript/react-css-in-js-nationjs.html) - Stop what you're doing and watch this. This was the talk that has informed and kicked off a staggering amount of innovation in the "CSS" world since it was given. While there are differing opinions on the execution (CSS Modules vs CSS in JS etc) the overview on what is wrong with a traditional approach to CSS is spot on.

* [How Instagram Works](https://www.youtube.com/watch?v=VkTCL6Nqm6Y) by [Pete Hunt](https://twitter.com/floydophone) - Can't overstate how many times I've returned to and watched this. A fantastic primer on some of the historical issues with the way we have collectively been writing web apps, and an overview of how Instagram approached fixing some of these issues.

* [Play nice with CSS tools and Methodologies](https://www.youtube.com/watch?v=-bZSTMLqf8Q) by [Brad Westfall](https://twitter.com/bradwestfall) - Breaks CSS down into Implementation, Ideology, Methodology which is a great way to think about the massive world of CSS.

* [Advanced Webpack](https://www.youtube.com/watch?v=MzVFrIAwwS8) by [Jonathan Creamer](http://jonathancreamer.com/) - I'm not new to Webpack anymore but this presentation gave me lots of insight and tricks to level up my chops.

* [The Case for CSS Modules](https://www.youtube.com/watch?v=zR1lOuyQEt8) by [Mark Dalgleish](http://markdalgleish.com/) - Webpack, PostCSS, BEM, React. This talk touches on all of these things and leveled me up on most. Filled my toolbelt with many newer techniques and tools.

* [Decomplexitying UI](https://www.youtube.com/watch?v=rI0GQc__0SM) by [Steve Luscher](https://twitter.com/steveluscher) - One of those "aha" moments when I realized just how deceivingly complex UI Development can be and _why_ React's approach addresses many of these issues.

* [Adaptation and Components](https://www.youtube.com/watch?v=m0oMHG6ZXvo) and [Thinking beyond “Scalable CSS”](https://www.youtube.com/watch?v=L8w3v9m6G04) by [Nicholas Gallagher](http://nicolasgallagher.com/) - Pretty anything by Nicholas Gallagher is on my 'drop everything and watch/read immediately' list. If you've missed the case for Components, or need to clarify or expand on a few points, these talks are good places to catch up. The analogy of the old radio in Thinking beyond Scalable CSS" is worth the watch alone!

* [Kick your CSS up a notch with PostCSS](https://www.youtube.com/watch?v=-_gIKdHYP3E) by [Max Stoiber](https://mxstbr.com/) - PostCSS was a bunch of concepts that I hadn't put together into a understanding of what it is before I found this video. 5 minutes later all those concepts had been linked and I felt comfortable taking on writing my own PostCSS Plugin. Not that I have. Yet.


### Articles

* [The media object saves hundreds of lines of code](http://www.stubbornella.org/content/2010/06/25/the-media-object-saves-hundreds-of-lines-of-code/) by [Nicole Sullivan](http://www.stubbornella.org/) - Although arguably a touch dated in its execution (given it was written in 2010) this was the first article that opened my eyes that a methodology should be applied to my at the time 'hack and thwack' approach to CSS. This was before BEM, SMCSS and other formalized approaches but the Media Object changed my conception of what good CSS could be.

* [About HTML semantics and front-end architecture](http://nicolasgallagher.com/about-html-semantics-front-end-architecture/) by [Nicholas Gallagher](http://nicolasgallagher.com/) - another oldie but a goodie. Fundamentals shouldn't change.

* [The End of Global CSS](https://medium.com/seek-ui-engineering/the-end-of-global-css-90d2a4a06284#.pxlwiao74) by [Mark Dalgleish](http://markdalgleish.com/) - The article that preceded the [The Case for CSS Modules](https://www.youtube.com/watch?v=zR1lOuyQEt8) listed above. Gets more into CSS Modules specifically, although some of the execution has changed since writing. (See the video for additional information).

* [It's Time for Everyone to Learn About PostCSS](http://davidtheclark.com/its-time-for-everyone-to-learn-about-postcss/) by [David Clark](http://davidtheclark.com/) - There are a lot of great [PostCSS](https://github.com/postcss/postcss) articles, this is just the one was the _straw that broke the camels back_ for me. ([Introduction to PostCSS](http://www.smashingmagazine.com/2015/12/introduction-to-postcss/) on [Smashing Mag](http://www.smashingmagazine.com/) is another good one). Whatever your introduction, PostCSS is going to continue to grow in influence in the CSS space in the future.


