<p align="center">
  <img src="/assets/logo.png?raw=true" width="128">
  <h3 align="center">It's a reading list</h3>
</p>

## Index

- [Index](#index)
- [Wisdom](#wisdom)
- [Performance](#performance)
- [JavaScript](#javascript)
- [React](#react)
- [Redux](#redux)
- [Video](#video)
- [UX](#ux)
- [HTTP](#http)

## Wisdom

- **Things I Learnt The Hard Way (in 30 Years of Software Development)**

     https://blog.juliobiason.net/thoughts/things-i-learnt-the-hard-way/

- **Lisping at JPL**

    http://flownet.com/gat/jpl-lisp.html

    "The situation is particularly ironic because the argument that has been advanced for discarding Lisp in favor of C++ (and now for Java) is that JPL should use "industry best practice." The problem with this argument is twofold: first, we're confusing best practice with standard practice. The two are not the same. And second, we're assuming that best (or even standard) practice is an invariant with respect to the task, that the best way to write a word processor is also the best way to write a spacecacraft control system. It isn't."

- **Reading Postmortems**

    https://danluu.com/postmortem-lessons/

    "If you care about building robust systems, the error checking code is the main code!"

- **Complexity Has to Live Somewhere**

    https://ferd.ca/complexity-has-to-live-somewhere.html

    "Complexity has to live somewhere. If you embrace it, give it the place it deserves, design your system and organisation knowing it exists, and focus on adapting, it might just become a strength."
     
**[Index](#index)**


## Performance

- **Idle Until Urgent**

     https://philipwalton.com/articles/idle-until-urgent/

     Provides a good look at common JavaScripe bottlenecks and how to improve them by using an "Idle Until Urgent" strategy whereby tasks are scheduled using `requestIdleCallback` unless they are needed earlier in which case they are evaluated immediately upon being required.
     

- **Big O Notation**

     https://www.interviewcake.com/article/python/big-o-notation-time-and-space-complexity
     
     A simple and quick explanation of Big O Notation with numerous examples.
 
 
- **Scheduling in React**

     https://philippspiess.com/scheduling-in-react/
     
     Similar to the **Idle Until Urgent** article above, this article digs into some advanced React scheduling features coming down the pipe. A good introduction to the future of some React APIs and a good article to keep tabs on as these scheduler features are developed. 
     

- **The Unseen Performance Cost of CSS-in-JS**

     https://calendar.perfplanet.com/2019/the-unseen-performance-costs-of-css-in-js-in-react-apps/
     
     In this article, I will attempt to demystify the high-level strategies of the most popular CSS-in-JS libraries, discuss the performance issues they may introduce on occasion and finally consider techniques that we can employ to mitigate them.

- **Ubiquity: The Fallacy of Premature Optimization**

    https://ubiquity.acm.org/article.cfm?id=1513451
    
    Randall Hyde argues that optimization is important even when memory and processor double regularly. Trying to do the optimization too early can be a futile time-waster.

- **Reflection on Performance**

    https://blog.nelhage.com/post/reflections-on-performance/
    
**[Index](#index)**


## JavaScript

- **In The Loop: JsConf Talk**

     https://www.youtube.com/watch?v=cCOL7MC4Pl0&feature=youtu.be

     This talk looks at the browser's event loop, the thing that orchestrates the main thread of the browser, which includes JavaScript, events, and rendering. We'll look at the difference between tasks, microtasks, requestAnimationFrame, requestIdleCallback, and where events land.


- **Anatomy of a Video Game**

     https://developer.mozilla.org/en-US/docs/Games/Anatomy
      
     While this article is focused on game programming specifically, it's a good exlanantion of how to efficiently schedule rendering and user input using `requestAnimationFrame` to achieve high frame rates. For this reason it's a good read for those using the `requestAnimationFrame` API for other applications.
      
- **Understand JavaScript’s “this” With Clarity, and Master It**

     https://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/
     
     This is simply the best article I've found about how **this** works in JavaScript.
     
- **A Bloatless Web**

     https://itnext.io/a-bloatless-web-d4f811c7991b

     An excellent discussion of how to cut down on JavaScript bloat on modern web apps. Includes some specific steps that can be taken to avoid unnecessary code caused by transpilers.
     
- **Metaprogramming in ES6: Symbols and why they're awesome** 

     https://www.keithcirkel.co.uk/metaprogramming-in-es6-symbols/

**[Index](#index)**


## React

- **React is Slow, React is Fast: Optimizing React Apps in Practice**

     https://marmelab.com/blog/2017/02/06/react-is-slow-react-is-fast.html

     An excellent overview of common performance pitfalls in React and how to solve them.
     
- **React as a UI Runtime**

     https://overreacted.io/react-as-a-ui-runtime/
     
     This one is long but it's an excellent deep dive into the concepts and thinking behind React. By the man himself, Dan Abramov.
     
- **Building Great User Experiences with Concurrent Mode and Suspense**

     https://reactjs.org/blog/2019/11/06/building-great-user-experiences-with-concurrent-mode-and-suspense.html

     This includes an excellent discussion on data fetching in a React app. 

**[Index](#index)**


## Redux

- **Wordpress Calypso: Our Approach to Data**

     https://github.com/Automattic/wp-calypso/blob/master/docs/our-approach-to-data.md

     The team behind Wordpress's new admin panel looks at their migration from emitters to Flux to Redux, and describes how they organize their state tree, use selectors to extract state, run queries with components, and persist their store state through refreshes.

**[Index](#index)**


## Video
- **A Digital Media Primer for Geeks Episode 1**

     https://www.xiph.org/video/vid1.shtml

     This first video from Xiph.Org presents the technical foundations of modern digital media via a half-hour firehose of information. One community member called it "a Uni lecture I never got but really wanted."

     The program offers a brief history of digital media, a quick summary of the sampling theorem, and myriad details of low level audio and video characterization and formatting. It's intended for budding geeks looking to get into video coding, as well as the technically curious who want to know more about the media they wrangle for work or play.

- **A Digital Media Primer for Geeks Episode 2**

     https://www.xiph.org/video/vid2.shtml

     Continuing the "firehose" tradition of maximum information density, Xiph.Org's second video on digital media explores multiple facets of digital audio signals and how they really behave in the real world.

     Demonstrations of sampling, quantization, bit-depth, and dither explore digital audio behavior on real audio equipment using both modern digital analysis and vintage analog bench equipment... just in case we can't trust those newfangled digital gizmos. You can also download the source code for each demo and try it all for yourself!

**[Index](#index)**


## UX
- **Why so much “science” used in design is bullshit: Android, Losada and Frankfurt.**

    http://mjparnell.com/bullshit_science_ux_design/
    
- **4 Rules for Intuitive UX**

    https://learnui.design/blog/4-rules-intuitive-ux.html
    
**[Index](#index)**

    
## HTTP
- **HTTP headers for the responsible developer**

    https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer

**[Index](#index)**
