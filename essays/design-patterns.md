---
layout: essay
type: essay
title: "Choosing Software Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2023-11-22
published: true
labels:
  - Design Patterns
---

## Keeping everything organized

Writing code is just as much an art as it is a science. Simply getting the right output is not enough when making industry-grade software. Creating code that is readable, efficient, and organized is the art of coding. In my opinion, this is a large part of what separates junior and senior developers.

This is where design patterns come in. I like to think of software design patterns as a philosophy on how best to organize the application. There are so many different design patterns that it is reductive to classify them by anything more specific. A design pattern is also an agreement between all developers on a project on how the code will be seperated and organized.

One of the most popular design patterns and one which I use often is the Model-View-ViewModel (MVVM) architecture. This architecture states that the view (UI), ViewModel (UI logic) and model (business logic and/or data) should be separate entities.
This is seen in many applications, even if it isn't usually referred to by that name.
For example, any web app that uses a separate backend and frontend usually loosely follows this architecture.
However, the most common use of this architecture is in mobile applications. Whenever I develop an Android application, I strictly follow this design pattern to keep my code readable and easily traceable.

<img width="400px" class="rounded float-start pe-4" src="../img/MVVMSchema.png">

source: geeksforgeeks.org

### Possible Issues with Design Patterns

Whenever design patterns are chosen for the development of an application, they can often be quite strictly enforced. This is due to the nature of design patterns. They are meant to act as a rule for how the application should be laid out.
Sometimes, however, this can lead to situations in which an objectively better solution gets invalidated due to its difference from the agreed design pattern. It can also stifle creativity or, if overused, be an unnecessary hindrance to development.

There is no one way for developers to succeed. Design patterns should most certainly be used in one way or another when designing complex software, but if overused in scenarios in which they aren't necessary, problems can arise. Software engineers must be able to make these decisions wisely.
