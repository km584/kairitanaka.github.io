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

I used ESLint with IntelliJ and touched on coding standards. First impressions are that even minor issues are flagged as code issues by coding standards. But now that I think about it, I would appreciate it if you pointed it out. Sometimes it's hard to tell if the code is inside the function of the loop. In the time it takes to clear the coding conventions, we can deal with each problem if we know the cause of the problem. In other words, you can shorten the time to start the problem without spending that much time. There is so much to learn and gain that it may be trivial to absorb the knowledge and write clean and understandable code, but what features will you be able to use when working on your own or in a group in the future? Coding standards make programming a more efficient use of your time as a result, because it makes it easier to understand when something goes wrong or when a problem arises.
