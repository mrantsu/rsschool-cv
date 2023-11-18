# Anton Sukhadolets

## Contact Info:
- tel: +48 792 302 263
- email: mrantonisu@gmail.com

### Summary
Hello, my name is Anton, and I am originally from Belarus. Currently, I am residing in Poland. The process of relocating has brought about significant changes in my life. While it hasn't been easy, I believe it presents new opportunities for both me and my family. Adapting to these changes is crucial.

In light of this situation, I've made the decision to transition to a new profession and gain fresh experiences. I've chosen to delve into front-end development, leveraging my existing knowledge in this field. Although I lack commercial experience, I am dedicated to expanding my skills daily. I engage in practical web projects, along with extensive reading of web documentation and articles, to enhance my expertise
In my learning I use such online resources as:
- codecademy
- codewars
- leetcode
- freecodecamp
- frontendmentor
- frameworks documetation, books
and other...

### Skills(this list contains I've ever used during my study process)
- HTML5
- CSS (including animations, flexbox, css grid and css variables, accessibility)
- JavaScript
- Chart.js
- jQuery
- Angular (basic)
- Sass/Scss
- LESS
- Git
- BEM methodology
- Gulp 4 (basic)
- Node.js (basic)
- Npm(basic)
- Figma
- Webpack

### Code example:
```
function smallEnough(a, limit){
 return a.every(elem => elem <= limit);
}
```
```
function filterHomogenous(arrays) {
  return arrays.filter(i => {
    return i.length === 1 || i.every(i => typeof i === 'number') && i.length !== 0 || i.every(i => typeof i === 'string') && i.length !== 0;
    })
}
```
```
const whosOnline = (friends) => {
  const resultObj = {};
  friends.forEach(i => {
    if (i.status === 'online' && i.lastActivity > 10) {
      if (resultObj.hasOwnProperty('away')) {
        resultObj.away.push(i.username);
      } else {
         resultObj.away = [i.username];
      }
    } else if (i.status === 'online' && i.lastActivity <= 10) {
      if (resultObj.hasOwnProperty('online')) {
        resultObj.online.push(i.username);
      } else {
        resultObj.online = [i.username];
      }
    } else {
      if (resultObj.hasOwnProperty('offline')) {
        resultObj.offline.push(i.username);
      } else {
        resultObj.offline = [i.username];
      }

    }
  })

  return resultObj;
}
```