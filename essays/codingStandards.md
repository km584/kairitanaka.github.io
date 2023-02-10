---
layout: essay
type: essay
published: true
title: "Coding Standards will help Programming"
date: 2023-02-09
labels:
  - ICS
  - code standards
---

<img class="img-fluid" src="../img/code picture.jpeg">

I didn't think much about coding standards while writing the program. When I wrote a program before, I didn't care about coding standards, just adding comments to make it easier to understand what the function was. I still think errors are the only thing you care about when writing programs, do coding standards really matter in writing programs?

So what exactly are coding standards? Coding standards are tools that minimize errors and help programmers write code that is cleaner, easier to read, and more efficient. I see this coding standard as a facility for software engineers to build code that is more advanced and makes the functionality of the code easier for others to understand. For example, this coding standard presents various code improvements, such as lack of space in the code, use of the same variables, and extra variables because the called function is not used in it, and makes the code more efficient. You can make it easy to understand when it is beautiful and others see the program.

```
const cities = [];

function averagePopulation(cities, place)

  let populationPlace = _.filter(cities, function(num){return num['island'] === place; });

  let max = _.max(populationPlace, function(num){return populationPlace.island})
```

I think coding standards are a very good way to improve the quality of your code and a very useful technique for learning to write clean and understandable code. This coding standard tells us what kind of problems there are in the code. If the data inside is the same, it may cause misunderstanding and the code may not be read correctly. So I think this coding standard will help you learn what kind of code causes problems, and you will be able to write more sophisticated code by using it repeatedly.

I used ESLint in IntelliJ and touched on coding standards. My first impression was that even if it was a minor problem, the coding standard would issue it as a problem in the code, so I didn't really understand it. And now it takes time to clear the coding standards, each problem can be dealt with if you understand what is causing the problem, but you do not know well what causes the problem of coding standards. There are a lot of coding standards and it takes time to solve them, but there is a lot to learn, so it may be a trivial thing to absorb knowledge from there and write code cleanly and clearly, but in the future I think it's useful because it makes it easier to understand which functions are available when working in groups.

