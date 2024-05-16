---
title: Scientific programming languages
date: 2024-04-18
math: true
image:
  placement: 2
  caption: 'Image credit: [**John Moeses Bauan**](https://unsplash.com/photos/OGZtQF8iC0g)'
---

# What does scientific programming mean?

First of all, scientific programming should be focused on an effective and correct solution to the problem. It could be argued that these requirements apply to all software. However, the question is the priority of the criteria. Let's say, if an office program runs not 0.25 seconds, but 1 second to process a transaction, then this is not as critical as, say, carrying out a calculation within a week or a month. The same applies to the correct execution of the program. It's one thing for a computer game to freeze, but it's a completely different thing if there is an error during the calculations that leads to incorrect conclusions or technological disasters.

![](featured.jpg)

# Basic moments

Here are some points to keep in mind when starting to program scientific problems.

Optimization of program texts. Very often, a small change in the program text can dramatically increase the speed of calculations. The optimizing compiler is not omnipotent.

Do not use external routines and libraries. Except in special cases, try to program the algorithms used yourself. Firstly, this will give a comprehensive understanding of the numerical method itself, and, secondly, by implementing it “for yourself” you can achieve the best result.

Sacrifice versatility for efficiency. Universality is one of the most beloved achievements of programming, but for scientific programming the construction of universal software systems is not always justified.

Use modern compilers. Not everything can be optimized by hand - modern optimizing compilers can seriously increase speed.

# Select a programming language.

Fortran has long been the language of scientific calculations. Indeed, this language has many advantages, but even more disadvantages. Such as:

The language of the old generation. This language was developed at the dawn of the computer era, so many important programming technologies, such as modularity, type checking, etc. are not implemented in it. Which leads to errors and difficulties during programming.

Many routine libraries are already outdated. Progress in the computer field is happening extremely quickly. Therefore, libraries developed for outdated computers may be useless.

Lack of mobility. Despite existing language standards, specific implementations of this language differ significantly.

# Benefits of C++

The choice of the C# language is motivated by the following factors:

Modern language. Programming is an area in which progress occurs very quickly. The C# language, on the one hand, absorbed the best features of the C++ and Java languages, and on the other hand, was created without the need to maintain compatibility with previous versions.

The power of the .NET platform. C# is the core language of the .NET platform, so when you program in C#, you are also programming in the .NET platform, which provides you with powerful, well-designed classes.

Efficiency of language. Surprisingly, programs written in C# running on .NET are very efficient applications. However, when developing complex programs, one should take into account not only the speed of program execution, but also the speed of program development, as well as the complexity of further modification. In this parameter, the C# language is significantly superior to the classical C++ language.

In recent years, there has been the emergence of a new computing paradigm - cloud computing, in which the program creator is completely abstracted from where the computing process will take place. Cloud computing refers to the availability of significant computing power available over the Internet on demand. At these facilities, located in data processing centers (DPCs), it is possible to deploy Internet applications, web services, data storage and processing services, etc. By concentrating computing power in economically attractive areas, widespread use of virtualization and automation of node health monitoring, cloud service providers can achieve significant economies of scale and high availability and reliability of the services provided.

A cloud application consists of a set of services running in a data center. In this case, all issues of launching services and maintaining their functionality are taken over by the computing support environment - the programmer is required to implement the appropriate program code and file with a description and perform deployment. Typically, a cloud application consists of computing components (this could be a web service, a web application, or a computing unit that does not require user interaction) and a data store, which we distinguish here from the term database because, due to the need scaling, non-relational storage is usually used. Computing components are typically programmed in a stateless model, which makes it possible, in the event of a failure, to restart the corresponding component without disrupting the operation of the application. In addition, the environment allows you to run the computing component on several virtual servers simultaneously and use load balancing to improve performance.

It should be noted that not every task can be efficiently computed on a cloud cluster in such an architecture. Unlike a traditional computer cluster, which has a high-speed data exchange channel between nodes, in this architecture the exchange is carried out through a low-speed external data storage. In theory, it is possible to organize direct network communication between compute role instances, but this approach is beyond the scope of this course. In any case, it should be understood that cloud computing is not a replacement for high-performance computing clusters, and the speed of data exchange between nodes is lower. However, there are a significant number of tasks that do not require significant communication between nodes during the computation process. As an example, we can consider independent enumeration problems, in which we can initially partition the search space into disjoint subspaces, which will be searched by independent computational roles.
