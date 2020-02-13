# Mykhailo Velykoselskyi
## *CV for a position of a Junior JavaScript Developer*
### contact info:
* Phone: __+380(68)126-59-81__, __+380(66)194-49-81__
* Telegram: __[t.me/unibreakfast](https://t.me/unibreakfast)__
* LinkedIn: [linkedin.com/in/unibreakfast](https://www.linkedin.com/in/unibreakfast)
* Facebook: [facebook.com/UniBreakfast](https://facebook.com/UniBreakfast)
* Skype: unibreakfast
* Email: mykhailo.velykoselskyi@gmail.com

---

### skills:
* __Strong Vanilla JavaScript (2 years+)__
* __HTML, CSS__
* __npm, Node.js, REST API__
* __Git, GitHub__
* JSON, Mongo DB
* PHP, MySQL, relational databases
* little experience with React, Vue, Angular, TypeScript, Webpack
* Python, C#, Forth, Lisp (limited knowledge)
* online/offline programming tutoring, pair programming
* advanced PC user for 25 years+

---

### code examples:
```js
const makeRepeatable =(fn, inter)=> {
  const start =()=> {
    stop(), fn()
    start.intId = setInterval(fn, inter)
  }
  const stop =()=> clearInterval(start.intId)
  return [start, stop]
}

const makeThrottled =(fn, delay)=> {
  const throttle =(...args)=> {
    clearTimeout(cancel.timer)
    cancel.timer = setTimeout(fn, delay, ...args)
  }
  const runNow =(...args)=> {
    clearTimeout(cancel.timer), fn(...args)
  }
  const cancel =()=> clearTimeout(cancel.timer)
  return [throttle, cancel, runNow]
}
```
* <sub>*__do note: I easily change my code style adapting to the people I teach or work with.__*</sub>

More on my GitHub: [github.com/UniBreakfast](https://github.com/UniBreakfast)

---

### education
* Rolling Scopes School
* easily 1k+ video lessons ranging from Crockford and Bob Martin to MPJ and Wes Bos
* 15+ online video courses on web-development and JavaScript programming
* 10+ books on JavaScript, Node.js, HTML, CSS (including "Eloquent JavaScript", "You Don't Know JS", etc.)
* 500+ hours in online tutoring (giving and receiving) and pair programming (as a driver but mostly as a navigator)
