# Day 01 learning of 40-days-of-javascript 
---
#### today's learning was too simple it's about setting-up enviornment to learn Javascript 
**1. Through Browser**
**2. Through Node env**

---

#### How Javascript got loaded into Browser through HTML
there are 3 ways in total , all using script tag ofcourse 
**1.`<script src="file.js"></script>`**
**2.`<script async src="file.js"></script>`**
**3.`<script defer src="file.js"></script>`**

the main differnce is all about the how javascript got loaded in browser and executed with DOM 

**1.** with normal script , when browser encounter `<scrip>`t tag , It immediately stops and started loadiing all the `JS` script and execute it then and there and after that it paint remaining DOM of `HTML`

**2.** with the help of `Async` attribute `JS` started loading simultaneously with `HTML` DOM , but once loading complete it execute it too , one problem got solved but execution problem persist .

**3.** Here comes the hero `defer` who exactly works like we all needed . it loads JS asynchronously and wait till all the DOM paint has done by the browser , then it execute the `JS` with the perfect `DOM`.

>These are all the major things in Day 01
