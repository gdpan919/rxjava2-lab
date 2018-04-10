# RX Java 2 Lab

This repository is a lab about RX Java 2 and how to build RX Java API.

## Teasing

Reactive programing combines functional programming and data streams. In other words it's a bit fuzzy...

RX Java 2 is a library implementing the reactive programing paradigm. In this lab, you learn how to use RX Java 2, the concepts, the operators and the good practices. It explains how RX Java 2 lets you build concurrent applications easily, how to manage errors... But RX Java 2 is not a silver bullet! 

This lab also covers how to propose a RX Java API. Indeed with the reactive movements, lots of blocking and synchronous API are no more usable. 

## Content

* RX Java 2
* Reactive thinking
* The RX Java type of streams
* The operators
* How to build RX API
* Schedulers and concurrency
* Testing

## Want to improve this lab ?

Forks and PRs are definitely welcome!

## Building

**Code**:

    mvn clean compile
    
**Documentation**:

    docker run -it -v $(pwd):/documents asciidoctor/docker-asciidoctor "docs/build.sh"    


