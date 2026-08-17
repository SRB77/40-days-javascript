# Day 01 learning of 40-days-of-javascript 
---
#### today's learning was too simple it's about setting-up environment to learn Javascript 
- Through Browser
- Through Node env

---

#### How Javascript got loaded into Browser through HTML
There are 3 ways in total, all using the script tag of course:

1. `<script src="file.js"></script>`
2. `<script async src="file.js"></script>`
3. `<script defer src="file.js"></script>`

The main difference is how JavaScript is loaded in the browser and executed with the DOM:

1. With a normal `<script>` tag, when the browser encounters it, parsing pauses; the script is fetched and executed immediately, which blocks further parsing and rendering.

2. With `async`, scripts are fetched in parallel with HTML parsing and execute as soon as they're ready — this can change execution order or run before the DOM is fully parsed.

3. With `defer`, scripts are fetched in parallel and executed after the HTML is parsed, preserving execution order and avoiding blocking rendering.

> These are all the major things in Day 01
