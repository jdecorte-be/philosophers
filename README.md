<header>
<h1 align="center">
  <a href="https://github.com/jdecorte-be/philosophers"><img src=".assets/banner.png" alt="philosophers" ></a>
  philosophers
  <br>
</h1>

<p align="center">
  <h1 align="center"> is a C project focused on philosophers, h1, aligncenter.
</p>

<p align="center">
<a href="https://github.com/jdecorte-be/philosophers/actions/workflows/c-cpp.yml">
    <img src="https://img.shields.io/badge/Build-status-238636?logo=github%20actions&logoColor=white&labelColor=000000"
         alt="Build status">
  </a>
<a href="https://github.com/jdecorte-be/philosophers">
    <img src="https://img.shields.io/badge/Lang-C-555555?logo=c&logoColor=white&labelColor=000000"
         alt="Lang C">
  </a>
<a href="https://github.com/jdecorte-be/philosophers/stargazers">
    <img src="https://img.shields.io/badge/Stars-github%20stars-yellow?logo=github&logoColor=white&labelColor=000000"
         alt="Stars github stars">
  </a>
<a href="https://github.com/jdecorte-be/philosophers/network/members">
    <img src="https://img.shields.io/badge/Forks-github%20forks-blue?logo=github&logoColor=white&labelColor=000000"
         alt="Forks github forks">
  </a>
</p>

<p align="center">
<a href="https://github.com/jdecorte-be/philosophers">
    <img src="https://img.shields.io/badge/Size-github%20repo%20size-informational?logo=github&logoColor=white&labelColor=000000"
         alt="Size github repo size">
  </a>
  <a href="https://github.com/jdecorte-be/philosophers">
    <img src="https://img.shields.io/badge/topic-aligncenter-66D9EF?logo=github&logoColor=white&labelColor=000000"
         alt="philosophers aligncenter">
  </a>
  <a href="https://github.com/jdecorte-be/philosophers">
    <img src="https://img.shields.io/badge/topic-c-66D9EF?logo=github&logoColor=white&labelColor=000000"
         alt="philosophers c">
  </a>
  <a href="https://github.com/jdecorte-be/philosophers">
    <img src="https://img.shields.io/badge/topic-h1-66D9EF?logo=github&logoColor=white&labelColor=000000"
         alt="philosophers h1">
  </a>
  <a href="https://github.com/jdecorte-be/philosophers/stargazers">
    <img src="https://img.shields.io/github/stars/jdecorte-be/philosophers?logo=star&logoColor=white&labelColor=000000&color=E6DB74"
         alt="philosophers stars">
  </a>
  <a href="https://github.com/jdecorte-be/philosophers/network/members">
    <img src="https://img.shields.io/github/forks/jdecorte-be/philosophers?logo=github&logoColor=white&labelColor=000000&color=66D9EF"
         alt="philosophers forks">
  </a>
</p>
<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#installation">Installation 🖥</a> •
  <a href="#tips-project">Tips project</a> •
  <a href="#project-documentation">Project documentation 📚</a>
</p>
</header>

<p align="center">
	<b><i>Basics of process threading, and how work on the same memory space.</i></b><br>
</p>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/jdecorte-be/42-Philosophers?color=lightblue" />
	<img alt="Number of lines of code" src="https://img.shields.io/tokei/lines/github/jdecorte-be/42-Philosophers?color=critical" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/jdecorte-be/42-Philosophers?color=yellow" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/jdecorte-be/42-Philosophers?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/jdecorte-be/42-Philosophers?color=green" />
</p>

---

Philosophers an individual project at [42](https://www.42.fr/42-network/) about introduction to the basics of process threading, and how work on the same memory space.
And learn about mutexes, semaphores, and shared memory.

## Introduction

In computer science, the dining philosophers problem is an example problem often used in concurrent algorithm design to illustrate synchronization issues and techniques for resolving them.

It was originally formulated in *1965 by Edsger Dijkstra* as a student exam exercise, presented in terms of computers competing for access to tape drive peripherals. Soon after, Tony Hoare gave the problem its present formulation

[More informations](https://en.wikipedia.org/wiki/Dining_philosophers_problem)

*Tips and good methodology to do the project at the bottom of the readme*

## Installation 🖥

To test the project, go to one of the folders __*philo_one*__, __*philo_two*__ or __*philo_three*__ and make a `make`. Then, you can test the project using an executable.

__usage :__

`./philo_one number_philosopher time_to_die time_to_eat time_to_sleep [number_of_time_each_philosophers_must_eat]`
arguments in square brackets are not required (number_of_time_each_philosophers_must_eat)

__exemple :__

`./philo_one 4 500 200 200`

I made a visual option, which makes it possible to have a prettier display, which reduces performance a little.
To use it, add the option __*-v*__ after the executable, this option is only available on __*philo_zero*__ (philo zero is identical to philo one, but it can handle the [-v] option)

__exemple :__

`./philo_zero -v 4 500 200 200`

![alt text](https://zupimages.net/up/20/39/8a98.png)

## Tips project

> ⚠️ **Warning**: Don't copy/paste code you don't understand: it's bad for you, and for the school. I have put my login in a lot of files to encourage you doing your own version. Have fun !

`Philo_one Thread and Mutex `
([good resolution diagram](https://www.zupimages.net/up/20/38/cp71.png))

![alt text](https://zupimages.net/up/20/38/is7q.png)


## Project documentation 📚

 __*[Use pthread (pthread_create | pthread_join) EN video](https://www.youtube.com/watch?v=uA8X5zNOGw8&list=PL9IEJIKnBJjFZxuqyJ9JqVYmuFZHr7CFM&index=2&t=0s)*__
 
 __*[Thread & Mutex EN video](https://www.youtube.com/watch?v=9axu8CUvOKY)*__

__*[Semaphore EN video](https://www.youtube.com/watch?v=ukM_zzrIeXs)*__

__*[Fork explain in FR](https://www.commentcamarche.net/faq/10611-que-fait-un-fork)*__ __*or*__ __*[Fork Wiki EN](https://en.wikipedia.org/wiki/Fork_(system_call))*__
