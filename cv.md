# Valkovich Anastasiya

<img src="avatar.jpg" alt="avatar" width="150"/>

### Contacts:
* Location: Minsk, Belarus
* Phone: +375 (33) 628-25-79
* E-mail: anastasiya.valkovich@mail.ru
* Discord: Anastasiya (@nvalkovich)
* GitHub: @nvalkovich

----
### About Myself:
Previously, my work was related to medicine. I worked in a histological laboratory, but I did not see the future in this for myself. I wanted to do intellectual work, learn and develop. I have discovered programming and began to study HTML, CSS, and then JS. Now I'm aiming to become professional Frontend developer and get a job in this specialty.

---
### Skills:
* HTML5 (basics)
* CSS3 (basics)
* JavaScript (basics)
* Git, GitHub
* VS Code

---
### Code example:
Description:
*Given an array of integers, find the one that appears an odd number of times.
There will always be only one integer that appears an odd number of times*.

```javascript
function findOdd(A) {
  const statistics = {};

  for (let i = 0; i < A.length; i++) {
    const value = A[i];

    statistics[value] = statistics.hasOwnProperty(value)
      ? statistics[value] + 1
      : 1;
  }

  for (const key in statistics) {
    if (statistics[key] % 2 !== 0) return +key;
  }
}
```
---
### Work experience:
Missing 

---
### Projects:
[CV#1. Markdown & Git](https://github.com/nvalkovich/rsschool-cv)

--- 
### Courses:
* Layout tutorial for beginners (HTML Basics and CSS Basics) on code.mu 
* Onlinе-intensive «Frontend Start» on itlogia.ru 
* JavaScript Manual on learnjavascript.ru (*in the process*)
* Modern JavaScript - From Zero to Junior Specialist (2022) on udemy (*in the process*)

--- 
### Language:
English level - A2
