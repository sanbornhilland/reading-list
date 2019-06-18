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
     
**[Index](#index)**


## Performance

- **Idle Until Urgent**

     https://philipwalton.com/articles/idle-until-urgent/

     Provides a good look at common JavaScripe bottlenecks and how to improve them by using an "Idle Until Urgent" strategy whereby tasks are scheduled using `requestIdleCallback` unless they are needed earlier in which case they are evaluated immediately upon being required.
 
 
- **Scheduling in React**

     https://philippspiess.com/scheduling-in-react/
     
     Similar to the **Idle Until Urgent** article above, this article digs into some advanced React scheduling features coming down the pipe. A good introduction to the future of some React APIs and a good article to keep tabs on as these scheduler features are developed. 
     

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

**[Index](#index)**


## React

- **React is Slow, React is Fast: Optimizing React Apps in Practice**

     https://marmelab.com/blog/2017/02/06/react-is-slow-react-is-fast.html

     An excellent overview of common performance pitfalls in React and how to solve them.
     
- **React as a UI Runtime**

     https://overreacted.io/react-as-a-ui-runtime/
     
     This one is long but it's an excellent deep dive into the concepts and thinking behind React. By the man himself, Dan Abramov.

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
    
**[Index](#index)**

    
## HTTP
- **HTTP headers for the responsible developer**

    https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer

**[Index](#index)**
