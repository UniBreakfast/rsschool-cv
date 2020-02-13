# Mykhailo Velykoselskyi
## *CV*
### contact info:
* Phone: +380(68)126-59-81, +380(66)194-49-81
* Telegram: [t.me/unibreakfast](https://t.me/unibreakfast)
* LinkedIn: [linkedin.com/in/unibreakfast](https://www.linkedin.com/in/unibreakfast)
* Facebook: [facebook.com/UniBreakfast](https://facebook.com/UniBreakfast)
* Skype: unibreakfast
* Email: mykhailo.velykoselskyi@gmail.com

---

### skills:
* Strong Vanilla JavaScript (2 years+)
* HTML, CSS
* Node.js, REST API
* Git, GitHub
* JSON, Mongo DB
* PHP, MySQL, relational databases
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
* <sub>*do note: I easily change my code style adapting to the people I teach or work with.*</sub>

More on my GitHub: [github.com/UniBreakfast](https://github.com/UniBreakfast)

---
