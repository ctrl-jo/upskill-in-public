# Web development roadmap

## Before you start

This original route starts with HTML and CSS, then JavaScript, before branching into frontend (the part people see), backend (the server-side work), or full stack (both). There is no fixed monthly deadline. React and Node.js are optional examples, not requirements for every web developer.

1. Open the MDN beginner material in [resources](resources.md). Start with a browser and a text editor or the lesson's online editor; no paid tool is needed.
2. For your first 15 minutes, create a page with a heading and a paragraph about a hobby. Save a short [daily log](../../../templates/daily-log.md) in [my-learning](../../../my-learning/README.md).
3. Plan two or three short sessions per week using the [study plan](../../../start-here/study-plan-template.md). Repeat a stage until you can show its checkpoint. If you already know a stage, try its checkpoint before skipping it.

## Stage 1: Page foundations

1. Learn HTML (HyperText Markup Language), which gives a page structure. Use headings, paragraphs, links, images with useful text descriptions, and forms with labels. Build a simple study profile using the MDN resource.
2. Learn CSS (Cascading Style Sheets), which controls appearance. Practice spacing, text size, the box model (how content, padding, and borders take up space), and flexible layouts.
3. Make the page responsive: readable on narrow and wide screens. Try it using only a keyboard and check that links and form controls can be reached. Accessibility means making the page usable by people with different needs.
4. Learn Git (file-change tracking) and GitHub (online project sharing) through the GitHub Hello World and Git resources. Save one focused change and inspect what changed; command-line Git can wait until you are comfortable editing in the browser.

Checkpoint: A readable profile page with a working link, labeled form, and narrow-screen layout, plus a saved change you can explain.

## Stage 2: JavaScript and browser behavior

1. Use MDN or freeCodeCamp from [resources](resources.md) to practice variables (named values), conditions (choices), loops (repeated actions), functions (reusable instructions), arrays (lists), and objects (groups of named values).
2. Learn the DOM (Document Object Model), the browser's representation of a page, and events such as clicks. Make a button add an item to a study checklist.
3. Learn how to find errors with the browser's developer tools. Add an empty-input message and check that the app keeps working after several clicks.
4. Learn HTTP, the request-and-response rules used by websites, and JSON, a text format for structured data. An API is a defined way for programs to exchange requests and results. Use a tutorial's public data example to practice fetching data, waiting for the response, and displaying loading or failure messages. Do not put secret keys in browser code.
5. Build a word counter or reading list without a framework (a set of tools and patterns for building apps). The [JavaScript folder](javascript/README.md) lists example ideas; your own project does not need to wait for those examples.

Checkpoint: A small interactive page that handles empty input and a failed data request, with an explanation of the code in your own words.

## Stage 3: Choose a direction

1. Pick one route below after Stage 2. It is fine to stay with frontend or backend; full stack is optional.
2. Follow that route's numbered steps. Choose one resource per topic from [resources](resources.md), rather than several courses at once.

| Direction | Focus | Starting requirement |
| --- | --- | --- |
| Frontend | Browser interfaces and interactions | Stages 1–2 |
| Backend | Server behavior, data, and access | Stages 1–2, especially JavaScript and HTTP |
| Full stack | Connecting a browser interface to a server | One small frontend project, then the backend route |

### Frontend route

1. Improve your existing JavaScript project with clear loading, empty, and error states. Split repeated code into functions or modules (separate reusable files).
2. If you want a component-based library, try React through its official Learn guide. A component is a reusable piece of a screen; state is data the screen remembers. Rebuild just one part of your project before moving the whole app.
3. Practice forms, keyboard use, and testing behavior: enter valid and invalid data and compare the result with what you expected. Learn an automated testing tool only after you can describe these checks.

Checkpoint: A small browser app you can use by keyboard and explain without following a tutorial line by line.

### Backend route

1. Use the official Node.js guide to learn how JavaScript runs outside a browser. Follow its setup lesson, then create a local server (a program that receives requests and sends responses).
2. Build a small API for a reading list. Practice creating, reading, updating, and deleting items. Check input on the server and return clear success and error responses.
3. Learn SQL (Structured Query Language) and database tables using the PostgreSQL tutorial. A database stores organized information. Start locally, store reading-list items, and confirm they remain after restarting your program. Use parameterized queries, which pass user input separately from SQL instructions.
4. Learn authentication (checking who someone is) and authorization (checking what they may do). Follow a maintained tutorial or library for sign-in instead of inventing password handling. Keep secrets outside source files and test that one user cannot change another user's data.

Checkpoint: A local API with persistent data, rejected invalid input, and a documented access rule. A hosted database service is optional after these basics; it is not a substitute for learning data and permissions.

### Full-stack route

1. Finish the frontend checkpoint and the backend checkpoint first.
2. Connect the browser app to your API. Keep secret credentials on the server and show useful messages while waiting or when a request fails.
3. Trace one action from the button, through the request, to the saved record and back to the screen.

Checkpoint: A reading-list app whose interface and server work together, with a clear explanation of where its data lives.

## Stage 4: Build, share, and continue

1. Build one original small project for your chosen route. Record setup steps, expected behavior, normal and failure checks, and one limitation using the [mini-project template](../../../templates/mini-project.md).
2. Keep the project and notes in [my-learning](../../../my-learning/README.md). Sharing source and screenshots is enough; hosting (running it online) is optional. Before hosting, review service costs and keep private information out of sample data.
3. Choose one next topic for your role: frontend performance and accessibility, backend reliability and data design, or full-stack deployment and monitoring (checking that the app stays healthy).

Checkpoint: Someone else can follow your project instructions and understand what you learned. Deeper role-focused projects are Planned — Coming soon; this beginner route is Available now.
