This is the main document, which will report all the progresses (and misfortunes) that will happen during this voyage :)

[Sat 19 Sep 2026]
Welcome to FireWooD, my personal journey trough trying to understand Frontend Web Dev!
As for right now I have never touched much about HTML, CSS, Javascript or so.

I intend to learn by:
* using free conventions that GitHub students packs offers
* using free online open sources
* if I cannot understand something, there's still an AI model which can lend me a hand
    explaining what I'm missing
* looking at cute cat pictures when I feel lost

As for right now, I plan down below to gather all infos and make an action plan on how
to proceed and what to aim for in order. 
I could divide it in phases based on how topics are structured and what courses offers. This is my first public personal project so I'm learning about how. to plan things and probably make some mistakes, but hey... what doesn't kill you makes you stronger ;)

For planning the journey I'm getting some help from AI, though I wanna make clear that everything below has been handwritted and analyzed by me. I wanna use it as a tool, not as something to replace my work. It can be better than me at finding sources and compare reviews, so I'm using it for this task, but it won't replace my work or my learning!

(Phase x: what I should learn                   [anticipated plans on what to do are written here!]       )

Phase 0: Envrionment + Web Fundamentals         [preparing this repo and everything useful]
Phase 1: HTML + CSS                             [personal portfolio on GitHub and customizations]
Phase 2: Javascript Foundation                  [calculator from scratch, maybe for something specific such as CFU]
Phase 3: Javascript Advanced + Web APIs         [wheather app, the best conversation started for everything :P]
Phase 4: React + TypeScript                     [full REACT app with routing + bees (API)]
(down below we'll go outside from frontend web dev but still I wanna report it here for a complete plan)
Phase 5: Node.js Backend                        [REST API with auth + database, I do hope PostGreSQL or SQLite]
Phase 6: Full-Stack integration                 [Dockerized full stack app with CI/CD]
Phase 7: WebRTC + WebAudio                      [the end of the main journey and a secret project :v]
Phase 8: Security + Performance                 [production-hardened app]
Phase 9: Rust (optional, we'll see about that)  [simple rust web API / learn what Rust is used for now]


### Phase 0: Envrionment + Web Fundamentals
This is the starting phase, spent settings things up and uderstanding how 
- goal: setting up the development envrionment and understanding the basics of web development

Sources:
1. MDN - How does the internet work? [ https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work ]
2. MDN - Getting started with the web [ https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web ]
3. Odin project pre-requisites (it's the second section) [ https://www.theodinproject.com/paths/foundations ]
4. Namecheap free domain (I'll just save it here cause GitHub students' pack offers one year for free) [ https://nc.me/ ]

Exit Criteria:
* explain what happens when you type an URl and press enter
* have set up VScode (I'm on gnu linux so CodeOSS) with proper extensions and know how to use Git. (For specific extension I'll keep a record laater on)
* know how to navigate trough files using a terminal (I already do luckily but if you're a beginner you should take some CS basics knowedge first)

### Phase 1: HTML + CSS
And now we can get started with the frontend! :D
- Semathic HTML structure
- CSS fundamentals
- Flexbox and CSS Grid for layout
- responsive design (media queries, fluid units, responsive images)
- basic accessibility (semantic tags, ARIA basics, contrast)
- CSS organization (custom properties, modern practices)

Sources:
1. Scrimba for learning HTML and CSS for free [ https://scrimba.com/learn-html-and-css-c0p ]
    * complete all modules and there should be about 5 projects
2. web.dev for keeping up with html and media insertion
    * this is more of a theory first course compared to Scrimba's hands on intro
    * this is Google's HTMl course which covers HTML, accessibility, forms, media and modern HTML features
3. web.dev for learning CSS [ https://web.dev/learn/css ]
    * it should be the most comprehensive modern CSS course avayable
    * complete all modules with focus on: box models, flexbox, grid, responsive design, custom properties (grid layout and flexbox are the most important topics)
4. The Odin Project [ https://www.theodinproject.com/paths/foundations ]
    * sections "HTML Foundations", "CSS Foundations" and "Flexbox"
    * TOP has great project description and forces to build without hand-holding
5. In case of confusion there are two additional reference source I found:
    * MDN CSS Styling basics [ https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics ]
    * MDN CSS Grid Layout guide [ https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout ]

exit Criteria:
- build a complete responsive web page from scratch (without using any framework, and not just because I don't know any framework for now)
- explain the CSS box model, cascade and specificity
- use Flexbox and Grid confidently for any layout
- use responsive images
- create a semantic, accessible HTML and be able to deploy a static webpage to GitHub Pages
- being able to read and uderstand most CSS code even if it's not written by yourself
- have a customized GitHub profile README (I saw some of my friend with very cool front pages so I wanna be able to do it myself, understood Archi?)

### Phase 2: JavaScript Foundation
Now it's time to understand deeply as a language, learning variables, functions, objects, arrays, closures and asyncronous programming.
- Javascript syntax and fundamentals
- functions, closures, scope
- objects, prototypes, classes
- arrays and arrays methods
- Asyncronous Javascript (callbacks, promises, async/await)
- Error handling
- Modern ES6+ features (destructing, modules)

Sources:
1. JavaScript.info for beginning to learn the language [ https://javascript.info/ ]
    * complete all Part 1 ("The JavaScript Language")
2. Scrimba's javascript course [ https://scrimba.com/learn-javascript-c0v ]
    * complete all modules for working on projects while learning
3. web.dev's javascript course [ https://web.dev/learn/javascript ]
    * this is another training option, I'll keep it here too but we'll see depending on how good i have become
4. The Odin Project's javascript course [ https://www.theodinproject.com/paths/foundations ]
    * another viable option for training on projects
5. Exercism (not exorcism :P) offers some exercises too [ https://exercism.org/tracks/javascript ]

exit Criteria:
- being able to explain closures, prototypes and this in Javascript
- write and debug javascript code
- use async/await and promises fluently
- manipulate the DOM
- being able to build an interactive application in javascript
- read and understand most javascript code I could encounter
- have completed several projects

### Phase 3: Javascript Advanced + Web APIs
This phase, from what I am able to understand for now, will put its focus on loop, fetch, storage, history (he said it! The name of the file) and Web APIs to build complex interactive applications.
- the event loop (miscotasks, macrotasks)
- advanced async patterns
- Fetch API and HTTP requests
- web storage (local storage and session storage)
- history API and routing
- web workers basics
- regular expressions
- JavaScript design patterns
- Error handling best practices
- testing fundamentals

Sources:
1. Javascript.info's comeback [ https://javascript.info/ ]
    * complete part 2 ("Browser: Document, Events, Interfaces")
    * this should be the best source for learning APIs 
2. Codesmith hgh level course [ https://csx.codesmith.io/ ]
    * callbacks and higher-order functions [ https://csx.codesmith.io/public/callbacks/workshop-callbacks ]
    * closure, scope and execution context [ https://csx.codesmith.io/public/closures/workshop-closures ]
    * object oriented programming [ https://csx.codesmith.io/ ]
    * asynchronous javascript [ https://csx.codesmith.io/ ]
3. MDN Javascript guide (optional addon) [ https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide ]
4. MDN additional content for useful parts:
    * Fetch:    https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
    * Storage:  https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API
    * History:  https://developer.mozilla.org/en-US/docs/Web/API/History_API
5. The Odin Project's fullstack JavaScript path [ https://www.theodinproject.com/paths/full-stack-javascript/courses/javascript ]

exit Criteria:
- explain the JavaScript event loop (microtasks vs macrotasks, how the browser schedules)
- use fetch API to make HTTP requests (GET, POST, PUT, DELETE) and error handling
- build a single page application with client-site routing (History API)
- use localstorage/sessionstorage to store data
- debug complex JavaScript applications using DevTools
- build a complete CRUD application in vanilla JavaScript

### Phase 4: React + TypeScript modern frontend
The goal now is to build type-safe component-based applications. This is done understanding React's mental model, hoocks, state management and ecosystem.
- React fundamentals (components, JSX, props, state)
- Hoocks (useState, useEffects, useContext, useReducer, useMemo, useCallback, useRef)
- React router for navigation
- State management (Context API, Redux (I need to learn what it is), Redux, React Query)
- TypeScript fundamentals
- React + TypeScript integration
- Component testing
- Styling approaches (CSS modules, styled-components, Tailwind(seems to be an option facultative to learn))
- Advanced state management (Redux toolkit, React Query)

! This is the part where GitHub education pack becomes very useful for advanced courses (Scrimba Pro and Frontend Masters)
Sources:
1. Full Stack Open [ https://fullstackopen.com/en/ ]
    * parts 0, 1, 2 to learn everything about React
2. Scrimba Pro (GitHub Student's Pack) [ https://scrimba.com/frontend-path-c0j ]
    * focus on React modules (they should be: Learn React, React router, Advanced React, React Projects)
3. Frontend Masters "complete intro to React v9" [ https://frontendmasters.com/courses/complete-react-v9/ ]
4. Full Stack Open part 9 (TypeScript) [ https://fullstackopen.com/en/part9 ]
5. Frontend Masters (TypeScript fundamentals) [ https://frontendmasters.com/courses/typescript-fundamentals-v4/ ]
    * this is a deep dive into TypeScript
6. web.dev's Learn React course [ https://web.dev/explore/react ]
    * optimization performance taught by Google's perspective
7. Full Stack Open part 6 (advanced state management) [ https://fullstackopen.com/en/part6 ]
    * after having learnt basic React state, this should teach how to manage complex state in large applications
8. (optional) The Odin Project's fullstack React path [ https://www.theodinproject.com/paths/full-stack-javascript ]
    * this should provide more pratical projects to test skills properly
9. (optional) Tailwind CSS [ https://frontendmasters.com/courses/complete-intro-tailwind/ ]
    * it's a common CSS framework, btw here's the link for offical documentation https://tailwindcss.com/docs

exit Criteria:
- explain React's mental model (components, re-rendering, virtual DOM, reconciliation)
- use all common hooks correctly (useState, useEffect, useContext, useReducer, useMemo, useCallback, useRef)
- Build a complete Reat application with multiple routes, forms and API calls
- Write TypeScript types for React components, props, state, and events
- explain when and why use useEffect (and when not to)
- Lift state up appropriately and avoid prop drilling
- Write basic tests for React components (using React Testing Library)
- Use Redux or React Query for complex state management
- Build a full React + TypeScript application from scratch

### Phase 5: Node.js backend + databases
- node.js fundamentals
- Express.js for API servers
- REST API design principles
- MongoDB (NoSQL) and PostgreSQL (SQL which I have already learnt at uni)
- Authentication (JWT sessions, bcrypt)
- API testing (Jest + Supertest)
- Envrionment variables and configuration
- Error handling and validation
- Deployment

Sources:
1. Full Stack Open part 3 ("Programming a server with Node.js and Express") [ https://fullstackopen.com/en/part3 ]
    * it should cover Node.js, Express, REST API, MongoDB, deployment, ESLint in a high quality course
2. Full Stack Open part 4 ("Testing Express servers, user administration") [ https://fullstackopen.com/en/part4 ]
3. Frontend Masters with API design in Node.js [ https://frontendmasters.com/courses/api-design-nodejs-v5/ ]
    * this should cover REST API design, TypeScript-first approach, Postgres, JWT auth, integration testing, and production deployment
4. Full Stack Open part 13 ("using relational databases") [ https://fullstackopen.com/en/part13 ]
    * for me it's good to exercise on PostgreSQL, migrations and queries optimizations
5. The Odin Project: Full Stack JavaScript path [https://www.theodinproject.com/paths/full-stack-javascript/courses/nodejs]
    * this is the Node.js part, it covers Node.js, Express, MongoDB and authentication
