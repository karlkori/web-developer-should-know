# Web developer should know
A list of skills and technologies

| level  | description |
|:--:|--|
| :baby: junior  | has a little commercial web development experience  |
| :construction_worker:  middle | can implement typical* projects without external supervision; can decompose a typical project and provide a detailed estimate to complete it  |
| :tomato: senior | is able to decompose any type of complex project into feasible tasks, has experience in different domains; can organize development, integration and delivery flows in a team |


- General

  - CS?
    
    Materials:
    
    Expected result:
    - [ ] Big O (time & space); why do we need this notation?; how to use? be able to to determine big O of operations of main data structures
    - [ ] Data structures: linked list, stack, queue, tree, graph, hash table (know pros and cons, be able to choose most suitable one to solve a given problem)
    - [ ] Know how base data structures is implemented in your language of choice
    - [ ] Know about algorithms on base data structures (is not required to remember in details, but undertand pros & cons)
    - [ ] Know and avoid N+1 problem
    - [ ] Recursion (stack overflow)
    
  - Testing
    
    Material:
    
    Expected result:
    
  - Git
    
    Materials:
    - [ ] [Git Book](https://git-scm.com/book/uk/v2)
    - [ ] [Git tutorial](https://www.codecademy.com/learn/learn-git)
    - [ ] [GuitHub Flow](https://guides.github.com/introduction/flow)
    
    Expected result:
    - [ ] :baby: Have an own github account
    - [ ] :baby: Understood how Git (or other Version control system) helps in development
    - [ ] :baby: How to clone an existing project/ How to create a new project
    - [ ] :baby: How to add new or/and changed files and create a commit
    - [ ] :baby: How to write a proper message to commit
    - [ ] :baby: How to create a branch, how to switch between branches
    - [ ] :baby: How to update a branch from remote repository 
    - [ ] :baby: How to merge changes from one branch to another
    - [ ] :baby: How to publish your changes to a remote repository
    - [ ] :baby: How to create a Pull request (understood the idea behind the pull request)
    - [ ] :baby: Know tools to see a diff, and resolve possible merge conflicts
    - [ ] :baby: stash, cherry-pick

  - Network
  
    Materials
    - [ ] [HTTP tutorial from Mozilla](https://developer.mozilla.org/uk/docs/Web/HTTP)
    - [ ] [HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)
    - [ ] [OSI model](https://www.geeksforgeeks.org/layers-osi-model/)
    
    Expected result:
    - [ ] :baby: HTTP vs HTTPS
    - [ ] :baby: CDN (content delivery networks) - why it can be useful
    - [ ] :baby: Know how to use ssh, dig, ping, curl, wget (no need to now all available parameters but know how these tools can help)
    - [ ] :construction_worker: HTTP/2 - what is new, and what problems it tries to solve
    - [ ] :construction_worker: Awareness about OSI model
    - [ ] :construction_worker: How DNS works, A, CNAME, MX...
    - [ ] :construction_worker: Know how to use different HTTP headers (caching, auth, content type, ...)


  - Security

    Expected result:
    - [ ] :baby: CORS, Why is it necessary?
    - [ ] :baby: XSS, CSRF
    - [ ] :baby: How to send a sensitive data securily via network
    - [ ] :baby: Know in general how authentication (session, token based) works
    - [ ] :construction_worker: Know in details how authentication, authorization works (session, tokens, JWT, OAuth...)


  - Extra
    
    Expected result:
    - [ ] :construction_worker: Docker usage (choose a proper base image, add required libs, soft, configs, code; build, run, attach to it, see logs...)
    - [ ] :construction_worker: scp, rsync, sftp

- Backend
  - Auth
  
    Materials:
      - [ ] :baby: [Json Web Tokens](https://jwt.io/)
      - [ ] :baby: [Safe password resets with JWT](https://www.smashingmagazine.com/2017/11/safe-password-resets-with-json-web-tokens/)
      
  - Databases
    
    Materials:
    - [ ] [SQL from A to Z](https://dev.to/helenanders26/sql-series-from-a-to-z-2pk9)
      
    Expected result:
    - [ ] :baby: SQL vs noSQL
    - [ ] :baby: SQL common commands (select, insert, delete, transaction, bulk load, dump, restore)
    - [ ] :construction_worker: Be able to understand the output of EXPLAIN command
    - [ ] :construction_worker: ACID
    - [ ] :construction_worker: OLTP vs OLAP
    - [ ] :construction_worker: Be able to build a database schema for a project (correct data types, indexes, foreign keys, data normalization)
    - [ ] :construction_worker: key-value databases: Redis, memcache; what they are applicable for?
      
  - Microsevices
  
    Materials:
      - [ ] :construction_worker: [12 factors](https://12factor.net/)

  - Specific to programming language
  
    - NodeJS

      Materials:
        - [ ] [nodejs.dev](https://nodejs.dev/)
        - [ ] [Typescript](https://basarat.gitbooks.io/typescript/content/)
        - [ ] [NVM](https://github.com/creationix/nvm)

      Expected result:
      - [ ] ES6+ basics
      - [ ] nvm, npm, package.json, package-lock.json - how to install and use
      - [ ] event loop, async/await, promises, try catch
      - [ ] understanding why static typing is useful
      

- Frontend
  - HTML5
    
    Materials:
    - [ ] [Mozilla HTML](https://developer.mozilla.org/uk/docs/Web/HTML)
    - [ ] [How browsers render page](https://habrahabr.ru/post/338840)
    - [ ] [Can I Use](https://caniuse.com)
    - [ ] UI frameworks
      - [ ] [Twitter Bootstrap](http://getbootstrap.com)
      - [ ] [Google Material](http://materializecss.com)
      - [ ] Whatever is popular now
    
    Expected result:
    - [ ] :baby: Be able to build a layout from picture (PSD, sketch) - the result must be "Pixel Perfect" - using correct fonts, sizes, colors, margins, paddings
    - [ ] :baby: How to build and use Forms (radio, checkboxes, inputs, especialy file uploading)
    - [ ] :baby: Trying different UI frameworks
    - [ ] :baby: Know why to make a semantic markup (SEO just simple understandig)
    
  - CSS3
  
    Materials:
    - [ ] [CSS tutotrial from Mozilla](https://developer.mozilla.org/uk/docs/Web/CSS)
    - [ ] [A guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox)
    - [ ] [SASS] https://tokar.ua/read/6672
    - [ ] Pre-,post-processors: 
      - http://sass-lang.com
      - http://lesscss.org
      - http://postcss.org
    - [ ] [CSS Tricks - useful articles](https://css-tricks.com)
    
    Expected result:
    - [ ] :baby: How to include CSS into HTML
    - [ ] :baby: CSS selectors, pseudoselectors
    - [ ] :baby: How to use Media queries and why (responsive design)
    - [ ] :baby: Mobile first
    - [ ] :baby: CSS animation
    - [ ] :baby: Webfonts
    - [ ] :baby: Flexbox / Grid
    - [ ] :baby: Crossbrowser validation
    - [ ] :baby: Try to use any CSS pre/post processors and why they might be useful

    
  - [ ] Javascript
  
    Materials:
    - [ ] [Cheatsheat](https://github.com/mbeaudru/modern-js-cheatsheet) - to quickly refresh knowledge
    - [ ] [JavaScript. Ядро](http://dmitrysoshnikov.com/ecmascript/javascript-the-core-2nd-edition-rus/)
    - [ ] [Basics](https://developer.mozilla.org/uk/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
    - [ ] [Tutorial from Mozilla](https://developer.mozilla.org/uk/docs/Web/JavaScript)
    - [ ] [Web API](https://developer.mozilla.org/en-US/docs/Web/API)
    
    Expected result:
    - [ ] :baby: How to include a javascript code into your HTML page
    - [ ] :baby: Data types; const, let, var
    - [ ] :baby: Syntax: conditions, iterations, functions, classes...
    - [ ] :baby: Variable scope, hoisting, IIFE, modules, "this", closures
    - [ ] :baby: Sync and async code execution (callbacks, promises, async/await)
    - [ ] :baby: JSON, XML
    - [ ] :baby: Cookie
    - [ ] :baby: Web API: 
      - [ ] :baby: Manipulating DOM elements: create, update, remove, move
      - [ ] :baby: Handling DOM events: click, hover, onKey...
      - [ ] :baby: Local and sesion storage, what is a difference
      - [ ] :baby: XMLHttpRequest, fetch
    - [ ] :construction_worker: Web API in more details: 
      - [ ] :construction_worker: geolocation
      - [ ] :construction_worker: media (camera access)
      - [ ] :construction_worker: canvas
      - [ ] :construction_worker: web workers
      - [ ] :construction_worker: service workers
      - [ ] :construction_worker: web sockets
    - [ ] :baby: Work with one popular js framework: angular, react, vue...
    - [ ] :construction_worker: Be able to build an app from scratch by using some popular js framework
    
  - [ ] Chrome dev tools
    
    Materials:
    - [ ] http://devtoolstips.com
   
    Expected result:
    - [ ] :baby: debugging code (debugger, console.log,...)
    - [ ] :baby: inspecting DOM elements
    - [ ] :baby: testing a layout on different screens (responsive design)
    - [ ] :construction_worker: debug application performance (memory usage/leaks, cpu  intensive operations)
    
