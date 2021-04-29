<p align="center">
  <img src="/assets/logo.png?raw=true" width="128">
  <h3 align="center">It's a reading list</h3>
</p>

## Index

- [Index](#index)
- [Wisdom](#wisdom)
- [Computer Science](#computer-science)
- [General Programming](#general-programming)
- [Organization](#organization)
- [Performance](#performance)
- [JavaScript](#javascript)
- [TypeScript](#typescript)
- [HTML/CSS](#htmlcss)
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
     
- **My Engineering Axioms**

    https://martinrue.com/my-engineering-axioms/

- **The Rise of Worse is Better**

    "The lesson to be learned from this is that it is often undesirable to go for the right thing first. It is better to get half of the right thing available so that it spreads like a virus. Once people are hooked on it, take the time to improve it to 90% of the right thing."

    https://www.dreamsongs.com/RiseOfWorseIsBetter.html

- **50 Short Product Lessons**

    https://cutle.fish/blog/50-product-lessons#anchor46

- **Technical Debt Quadrant**

    A useful explanation of how to conceive of the Technical Debt metaphor and different kinds of Technical Debt.

    https://martinfowler.com/bliki/TechnicalDebtQuadrant.html
    
- **New Evidence That British Workplaces Are Losing Viewpoint Diversity**

    "However, organizations can depolarize. Leaders and communicators can influence this process by creating a sense of common purpose, firmly rooted in a clear and reassuring view of the future, in which everyone understands the role they have to play and all voices are listened to, even if they don’t feel confident about speaking up."

    https://www.ethicalsystems.org/new-evidence-that-british-workplaces-are-losing-viewpoint-diversity/

**[Index](#index)**

## Computer Science

- **Comprehensive Guide to Learn Computer Science Online**

  https://qvault.io/2020/11/18/comprehensive-guide-to-learn-computer-science-online

**[Index](#index)**

## General Programming

- **Flattening Arrow Code**

    https://blog.codinghorror.com/flattening-arrow-code/

    An explanation of why arrow code is bad and some good strategies for dealing with it.

**[Index](#index)**

## Organization

- **Product-Centric is Just as Bad as Sales Driven**

    https://itamargilad.com/product-led/

    A common complaint I hear from product folk is that management is too “sales-driven”. It is a common ailment indeed, but I can tell you that the opposite condition, the strictly “product-focused” company, is pretty bad too. Both companies suffer from over-focus and a narrow worldview. 

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

- **What forces layout / reflow**

    This is an extremely helpful (and maintained) list of properties that cause layouts and reflows, along with a number of good source to help avoid layout thrashing.

    https://gist.github.com/paulirish/5d52fb081b3570c81e3a
    
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

- **Vanilla JS Toolkit**

    https://vanillajstoolkit.com/reference/

    A great resource for brushing up on fundamentals and no-nonsense JS stuff. JS-Free Components is short but good resource for how to do some common things without JS.
    
- **From JavaScript to WebAssembly in three steps**

    https://engineering.q42.nl/webassembly/

**[Index](#index)**

## TypeScript

- **Tackling TypeScript: Upgrading from JavaScript**

    https://exploringjs.com/tackling-ts/index.html

- **React TypeScript Cheat Sheet**

    https://react-typescript-cheatsheet.netlify.app/docs/basic/setup

**[Index](#index)**

## HTML/CSS

- **Every Layout**

    https://every-layout.dev/

    A number of example layouts and how to create them using minimal CSS and HTML. Also includes several lessons on good fundamentals that are very informative.

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
     
 - **Digital Video Introduction**
 
     https://github.com/leandromoreira/digital_video_introduction
     
     A gentle introduction to video technology, although it's aimed at software developers / engineers, we want to make it easy for anyone to learn.
     
**[Index](#index)**


## UX
- **Why so much “science” used in design is bullshit: Android, Losada and Frankfurt.**

    http://mjparnell.com/bullshit_science_ux_design/
    
- **4 Rules for Intuitive UX**

    https://learnui.design/blog/4-rules-intuitive-ux.html

- **UI Playbook**

    A helpful resource that explains the behaviour of basic UI elements, and how to make them accessible etc.

    https://uiplaybook.dev/
    
- **Microcopy**

    https://steamclock.com/blog/2020/10/microcopy/

### ToggleSwitches

- Control boolean state
- Switches are for System States (not local)
- Switches should have immediate effect
- Label copy should be obvious (user’s shouldn’t have to flip the switch to discover what it does)
- Labels should describe what the control will do when the switch is on
- https://www.justinmind.com/blog/toggle-design-patterns-examples/
- https://developer.yoast.com/blog/when-to-use-toggle-switches/
- https://www.nngroup.com/articles/toggle-switch-guidelines/
    
**[Index](#index)**

    
## HTTP
- **HTTP headers for the responsible developer**

    https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer

**[Index](#index)**
