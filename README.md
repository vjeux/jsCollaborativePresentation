#jsCollaborativePresentation

I, [Christopher Chedeau](http://blog.vjeux.com/) am currently a student at [EPITA](http://epita.fr/). 
It's a computer science school with is a high focus on C and C++. 
Many students feel that low-level C is the holy graal and web development, with its dynamic language Javascript,
is only good for noobs. I am going to make a **1 hour conference** in order to prove them wrong!

While I could go the standard way and write the slides myself, I believe that the spirit of the web is community. 
This is why I would like to start an **experiment: Can we write together slides for a Javascript presentation?**

## Let me see!

The latest version of the presentation is available here:

- http://vjeux.github.com/jsCollaborativePresentation/

I will answer comments and questions on the [Hacker News thread](...). I will update my Twitter [@Vjeux](http://twitter.com/#!/Vjeux) with updates.

## What?

The public:

  - 3rd-5th year students in a Computer Science school
  - They know very well about programming (no need to explain loops)
  - They know very well about C & C++

The content:

  - Javascript, **the language**
  - Show what sexy we can do in Javascript compared to C++
  - Examples of subjects: 
  [Continuation Passing Style](http://en.wikipedia.org/wiki/Continuation-passing_style), 
  [Memoization](http://en.wikipedia.org/wiki/Memoization), 
  [Functional Programming](http://en.wikipedia.org/wiki/Functional_programming),
  [Method Chaining](http://ejohn.org/blog/ultra-chaining-with-jquery/),
  [Private Members](http://javascript.crockford.com/private.html) ...

What this presentation is **not** about:

  - HTML5 features (WebGl, Audio ...) and libraries in general. (You can use them as examples however).
  - The bad parts: the goal is to promote Javascript :)
  - CoffeeScript
  - Learning how to program

## How to contribute?

Let's say you want to add a slide about memoization:

  - [Fork the project](https://github.com/vjeux/jsCollaborativePresentation/fork)
  - Copy **slides/hook.html** to **slides/memoization.html** (Note: Change **memoization** by the name of your technique ...)
  - Open index.html and add the file
  
```  
  /* Add your slides here */
  include('slides/intro.html');
  include('slides/hook.html');
  // ...
  include('slides/memoization.html');
```
  - See the presentation at http://**username**.github.com/jsCollaborativePresentation
  - Edit **slides/memoization.html** to make it rock!
  - Commit
  - In your github project page, click the **Pull Request** link at the top right
  - Fill a short description and submit

You are done! Just give me some minutes to merge it with the live repo :)

## Final Remarks

  - The name of all the contributors will appear in the last slide.
  - I will make the talk during September and record it. It will be in French. (I wish I could present it in English during the [jsConf.eu](http://jsconf.eu/2011/)!)
  - I'm pretty sure some people will ask what license the presentation is ... I have no idea, please suggest one :)
  - I reserve the right to forge the final presentation as I wish. Sorry in advance if your slides are edited / not taken.

## Tools that power the presentation
  - [DeckJS](http://imakewebthings.github.com/deck.js/)
  - [jQuery](http://jquery.com/)
  - [Modernizr](http://www.modernizr.com/)