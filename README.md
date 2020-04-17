# Curated Rust
This is a guided walkthrough of the resources that I used to learn Rust. It is being added to incrementally as I myself learn rust over the next couple of weeks and months.

Some of the days, there are extra material. This is for material that is either not free, material that does not add anything new
, or only elaborated on previously covered topics.

## Week 1: Introduction and getting started
This is our introduction to Rust. It will cover a lot of the fundamentals of Rust and when this week is behind us, we will already be able to start writing software. 
During this week we will be watching a lot of video and we will be doing quite a bit of reading.
Some smaller exercises will also pop up during this week so get ready to code!

### Week 1, Day 1: What is Rust? (~ 1 hour)
So. For this first couple of days we will get to know a lot of things about Rust and we will get to travel 
to different parts of Rust. Try to relax. It's important that you **don't try too hard to learn anything**. 
Just sit back and try to enjoy it. Things will become more clear as we go. 

You probably won't understand all of the material for today, and that's totally fine. If you do understand everything, then great, otherwise you will find that it will all be comperhensible in time, we will come back to some of 
this material later on.

* 📺 1h 3min: Watch [Considering Rust - Jon Gjengset](https://www.youtube.com/watch?v=DnT-LUQgc7s)

### Week 1, Day 2: Getting started (~ 1 hour)
Time to get started. Start off by watching a short video on Rust. Then we continue reading through the introduction (section 1) [Introduction - The Rust Programming Language](https://doc.rust-lang.org/stable/book/ch00-00-introduction.html),
this will have you create not one, but two Hello World! apps.
We then do a bit more intro reading by reading pages sections 1 Why Rust? and 2 Type Safety from [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf).

* 📺 6 min: Watch [Rust and the Future of Systems Programming](https://www.youtube.com/watch?v=8EPsnf_ZYU0)
* 📚 20 min: Read through [Introduction - The Rust Programming Language](https://doc.rust-lang.org/stable/book/ch00-00-introduction.html)
* 📚 10 min: Read through the first and second secions of [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf); Why Rust? and Type Safety.
* 📚 10 min: Read through the introduction of [A Gentle Introduction To Rust](https://stevedonovan.github.io/rust-gentle-intro/readme.html)
* 📚 15 min: Checkout the Hello World example of [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/hello.html). Read 1.1 Comments but skip section 1.2 Formatted Print for now.

### Week 1, Day 3: Variables (~ 1 hour 10 minutes)
Now we are actually about to write our first pieces of software. Let's get into it!

* 📚 25 min: Read [2. Programming a Guessing Game](https://doc.rust-lang.org/stable/book/ch02-00-guessing-game-tutorial.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 📚 10 min: While we are talking about random stuff anyway, head over to Rust Cookbook and read [Generate random numbers](https://rust-lang-nursery.github.io/rust-cookbook/algorithms/randomness.html#generate-random-numbers). Try to understand the code, but don't spend too much time digging into the details.
* 📚 7 min: Read [3.1 Variables and Mutability](https://doc.rust-lang.org/stable/book/ch03-01-variables-and-mutability.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 💻 10 min: Setup [Rustlings](https://github.com/fmoko/rustlings).
* 💻 15 min: Do exercises *variables1*, through *variables6* from the [Rustlings](https://github.com/fmoko/rustlings) Course
* 📚 2 min: Read about [constants](https://doc.rust-lang.org/stable/rust-by-example/custom_types/constants.html) in the [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example)
* 📚 5 min: Read all the sections of [Variable Bindings](https://doc.rust-lang.org/stable/rust-by-example/variable_bindings.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/hello.html)

### Week 1, Day 4: Types, Functions and flow control (~ 1 hour 30 minutes)
* 📚 8 min: Read [3.2 Data Types](https://doc.rust-lang.org/stable/book/ch03-02-data-types.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 💻 5 min: Read all the sections of [2. Primitives](https://doc.rust-lang.org/stable/rust-by-example/primitives.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html), skip the activity for section '2.2 Tuples' for now, we will get back to it.
* 📚 8 min: Read [3.3 Functions](https://doc.rust-lang.org/stable/book/ch03-03-how-functions-work.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 📚 1 min: Read [7. Expressions](https://doc.rust-lang.org/stable/rust-by-example/expression.html) in the [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html) 
* 📚 1 min: Read [3.4 Comments](https://doc.rust-lang.org/stable/book/ch03-04-comments.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 📚 1 min: Read [1.1 Comments](https://doc.rust-lang.org/stable/rust-by-example/hello/comment.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html)
* 📚 10 min: Read [3.5 Control Flow](https://doc.rust-lang.org/stable/book/ch03-05-control-flow.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html). Do not do the exercises at the very end, we will do them in a minute, but first read about control flow also in Rust By Example.
* 💻 10 min: Read sections [8.1 if/else](https://doc.rust-lang.org/stable/rust-by-example/flow_control/if_else.html) through [8.4 for and range](https://doc.rust-lang.org/stable/rust-by-example/flow_control/for.html) of [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html). Go ahead and write up your own version of FizzBuzz!
* Go back to to [the Summary of 3.5 Control Flow](https://doc.rust-lang.org/stable/book/ch03-05-control-flow.html#summary) and implement those three small programs:
  - 💻 5 min: Convert temperatures between Fahrenheit and Celsius
  - 💻 15 min: Generate the nth Fibonacci number
  - 💻 15 min: Print the lyrics to the Christmas carol "The Twelve Days of Christmas"
* 💻 15 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *If1*, *functions1* through *functions5*, *test1* and *primitive_types1*, *primitive_types2*. Stop there, we will continue with *primitive_types3* later on.

All done? Great job! 🎉 
If this took you three hours, rather than an hour and a half, don't worry about it. It's not a contest!

### Week 1, Day 5: Taking a step back (~ 1 hour)
Now we are getting into parts of Rust that many find confusion and difficult. Therefore we will spend more time on this. 
We start off by looking at two presentations. I know, sometimes its hard co stay awake going through these. Check one of them out today, and look at the other tomorrow.

* 📺 1h: Watch [What Is Rust? - Yehuda Katz](https://www.infoq.com/presentations/rust-gc/)

### Week 1, Day 6: Even more video! (~ 40 min)
Bring out the popcorn, another video, just as promised yesterday!
Don't worry if you dont understand every detail in this video. We are heading into a part of rust that many find quite confusion and hard, namely Ownership and Borrowing. These two videos; the one you watched yesterday, and the one you will be watching now, will set you up to better understand the material to come. We will be taking a couple of days to go over this area, as it is quite advanced, but also very fundamental.

* 📺 40 min: Watch [A Case for Oxidation: The Rust Programming Language - Sergio Benitez](https://www.youtube.com/watch?v=cDFSrVhnZKo)

### Week 1, Day 7: Ownership and borrowing (~ 1 hour)
Take your time while reading these next chaptsers. They are truly fundamental and the more time you put into understanding these concepts now, the easier it will be later on.
* 📚 20 min: Read [4.1 What is Ownership?](https://doc.rust-lang.org/stable/book/ch04-01-what-is-ownership.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html).
* 📚 10 min: Read [4.2 What is Ownership?](https://doc.rust-lang.org/stable/book/ch04-02-references-and-borrowing.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html).
* 📚 10 min: Read [4.3 The Slice Type](https://doc.rust-lang.org/stable/book/ch04-03-slices.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html).
* Read the same material from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html), please note that we are skipping 15.4 Lifetimes for now, we'll get back to it.
  - 📚 1 min: [15. Scoping rules](https://doc.rust-lang.org/stable/rust-by-example/scope.html)
  - 📚 3 min: [15.1 RAII](https://doc.rust-lang.org/stable/rust-by-example/scope/raii.html)
  - 📚 2 min: [15.2 Ownership and moves](https://doc.rust-lang.org/stable/rust-by-example/scope/move.html)
  - 📚 3 min: [15.3 Borrowing](https://doc.rust-lang.org/stable/rust-by-example/scope/borrow.html)
* 💻 10 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *primitive_types4*, *primitive_types5* and *primitive_types6*.

#### 👑 Extra
* 💻 15 min: Do the *Raindrops* exercise on [Exercism](https://exercism.io/)
* 📺 8 min: Watch [Learning Rust: Memory, Ownership and Borrowing](https://www.youtube.com/watch?v=8M0QfLUDaaA)
* 📰 10 min: [Rust ownership, the hard way](https://chrismorgan.info/blog/rust-ownership-the-hard-way/)
* 📰 10min: [A closer look at Ownership in Rust](https://blog.thoughtram.io/ownership-in-rust/)

## Week 2: It's getting more advanced
Good job! We have not gotten through the first week of Rust. We have learned the basics and also written some code. 
Since last week ended with us watching a bunch of video, we will start this week off by doing some programming.

After the short break of Day 1, we will try to rush ahead a bit. Some of the areas won't make sense until you are through them all. Therefore we want to get through the more advanced subjects of Structs, Enums, Pattern matching, error handling, iterators and collections pretty quickly only to circle back and go over them all again.

### Week 2, Day 1: Nothing new just plain programming (~ 1 hour, 10 min)
No new content today. Instead we will just do a couple of programming exercises to get us more comfortable writing actual code.
* 💻 30 min: Do as many Project Euler problems that you can fit in 30 minutes.  [Project Euler](https://projecteuler.net). Don't worry about how many you actually finish. This is aimed to get us used to writing actual code.
* 💻 20 min: Do the problem called Matching Brackets on [Exercism](https://exercism.io/)
* 💻 20 min: Do the problem called Proverb on [Exercism](https://exercism.io/)

#### 👑 Extra
If you have more time keep doing project Euler challenges. Wait a bit with doing more of the Exercism exercises, we will learn some other Rust features, such as pattern matching, enums and structs, that will help you do those challenges later.

### Week 2, Day 2: Structs and methods (~ 1 hour)
* 📚💻 25 min: Read all the sections of [5. Using Structs to Structure Related Data](https://doc.rust-lang.org/stable/book/ch05-00-structs.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html). Follow along by writing the code yourself.
* 📚 5 min: Read [3.1 Structures](https://doc.rust-lang.org/stable/rust-by-example/custom_types/structs.html) in [Rust By Example] (https://doc.rust-lang.org/stable/rust-by-example/index.html)
* 📚 5 min: Read [9.1 Methods](https://doc.rust-lang.org/stable/rust-by-example/fn/methods.html) in [Rust By Example] (https://doc.rust-lang.org/stable/rust-by-example/index.html)
* 💻 30 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *structs1*, *structs2*, *strings1*, *strings2* and *test2*.

We will get back to more about structs very soon. So, if you have not fully wrapped your head around all of this, don't worry.

### Week 2, Day 3: Enums and Pattern Matching (~ 1 hour, 20min)
* 📚 15 min: Read all the sections of [Enums and Pattern Matching](https://doc.rust-lang.org/book/ch06-00-enums.html) from [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html)
* 💻 20 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *enums1*, *enums2* and *enums3*.
* 📰 15 min: Read [Mixing matching, mutation, and moves in Rust](https://blog.rust-lang.org/2015/04/17/Enums-match-mutation-and-moves.html). Don't worry if you don't understand it all. It's quite a though read!
* 💻 30 min: Do the *Leap* and the *Matching Brackets* exercises on [Exercism](https://exercism.io/)

### Week 2, Day 4: Collections
### Week 2, Day 5: Error Handling
### Week 2, Day 5: Generic Types, Traits and Lifetimes
### Week 2, Day 7: Iterators and closures

## Week 3: More fundamental stuff
### Week 3, Day 1: Recap
### Week 3, Day 2: Itertools
### Week 3, Day 3: Coding!
### Week 3, Day 4: 
### Week 3, Day 5: 
### Week 3, Day 6: 
### Week 3, Day 7: 

## Week 4: I/O
### Week 4, Day 1: 
### Week 4, Day 2: 
### Week 4, Day 3: I/O and Tokio
### Week 4, Day 4: Filesystem and Processes
### Week 4, Day 5: The I/O Project
### Week 4, Day 6: Understanding Ripgrep
### Week 4, Day 7: Automated testing

## Week 5: Cleaning up
### Week 5, Day 1: 
### Week 5, Day 2: 
### Week 5, Day 3: 
### Week 5, Day 4: 
### Week 5, Day 5: 
### Week 5, Day 6: Box, heap and pointers
### Week 5, Day 7: Macros

## Week 6: Concurrency and networking 
### Week 6, Day 1: Threads and concurrency
### Week 6, Day 2: Channels
### Week 6, Day 3: Networking
### Week 6, Day 4: Building a TCP/IP Server
### Week 6, Day 5: Building a TCP/IP Server continued.
### Week 6, Day 6: Async/Await
### Week 6, Day 7: Async/Await continued.

## Week 7: 
### Week 7, Day 1: Threads and concurrency
### Week 7, Day 2: Channels
### Week 7, Day 3: Networking
### Week 7, Day 4: Building a TCP/IP Server
### Week 7, Day 5: Building a TCP/IP Server continued.
### Week 7, Day 6: Async/Await
### Week 7, Day 7: Async/Await continued.


## Week 8: Web stuff
### Week 8, Day 1: Serialization and deserialization with JSON
### Week 8, Day 2: Serde
### Week 8, Day 3: Web-stuff
### Week 8, Day 4: Building a Web Server
### Week 8, Day 5: Building a Web Server continued.
### Week 8, Day 6: Introduction to WASM
### Week 8, Day 7: WASM continued.

## Week 9: Unsafe and interoperability
### Week 9, Day 1: Unsafe 
### Week 9, Day 2: Unsafe continued
### Week 9, Day 3: 
### Week 9, Day 4: 
### Week 9, Day 5: 
### Week 9, Day 6: 
### Week 9, Day 7: 

## Upcoming
### Reading the documentation
### Modules, packages, cargo and crates
### Regular expressions
### Reading code Regex
### Rocket 1
### Rocket 2
### CSV Files
### Reading code Ripgrep
### Databases, postgres
### Databases, redis
### Reading code Diesel
### Advanced Traits
### Python and Rust
### C and Rust
### C++ and Rust
### Java & Rust
### A bit bigger app
### A bit bigger app continued

## To be sorted
When we have done structs:
* 💻 min: Read [1.2 Formatted Print](https://doc.rust-lang.org/stable/rust-by-example/hello/print.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html)

https://gist.github.com/brson/a324c83a6af6a8a78dfaa9d33eb9b48e

https://techyaks.com/rust-all-ldconf.html

Video about memory safety etc. 38 minutes. [A Case for Oxidation](https://www.youtube.com/watch?v=cDFSrVhnZKo)

Video about ownership and borrowing. 1h.
Watch [What is Rust?](https://www.infoq.com/presentations/rust-gc/) [Video 1h]
## General 
* [Learn Rust](https://www.rust-lang.org/learn)
* [The Rust Programming Language](https://doc.rust-lang.org/stable/book/)

## Reference
* [Restonomicon](https://doc.rust-lang.org/stable/nomicon/)

## Books
* [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf)
* [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/)

## Courses
* [Learn Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/)
* [Rust in 7 Programs](http://aml3.github.io/RustTutorial/)
* [24 days of Rust](http://zsiciarz.github.io/24daysofrust/index.html)
* [Gentle Introduction to Rust](https://stevedonovan.github.io/rust-gentle-intro/readme.html)
* [Rust Basics](https://stepik.org/lesson/9268/step/1)
* [Rust Fundamentals](https://www.pluralsight.com/courses/rust-fundamentals)
* [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/)

## Web application / Project
* [A web application completely in Rust](https://medium.com/@saschagrunert/a-web-application-completely-in-rust-6f6bdb6c4471)
* [Rust Solution to the Mars Rover Challenge](https://github.com/cobbinma/mars_rover_/blob/master/README.md)

## Exercises
* [Rustlings](https://github.com/fmoko/rustlings/blob/master/README.md)
* [Exercism](https://exercism.io)
* [Rosetta Code](http://rosettacode.org/wiki/Rosetta_Code)
* [Project Euler](https://projecteuler.net)

## Tutorials
[Rust for Systems Programmers](https://github.com/nrc/r4cppp?ref=hackr.io)

## Articles
* [Two years with Rust](http://brooker.co.za/blog/2020/03/22/rust.html)
* [Half hour to learn Rust](https://fasterthanli.me/blog/2020/a-half-hour-to-learn-rust/)
* [Hoverbear Consulting # Rust](https://hoverbear.org/tags/#rust)

## Other resources
* [Rust Blog](https://blog.rust-lang.org)
* [Rust on Reddit](https://www.reddit.com/r/rust/)
* [This week in Rust](https://this-week-in-rust.org)
* [New Rustaceans (Podcast)](https://newrustacean.com)
* [Rust Playground](https://play.rust-lang.org)

## Videos
* [Learning Rust: Memory, Ownership and Borrowing](https://www.youtube.com/watch?v=8M0QfLUDaaA)
* [Rust Crash Course | Rustlang](https://www.youtube.com/watch?v=zF34dRivLOw)
* [Safe Systems Programming with Rust](https://www.youtube.com/watch?v=P3sfNGtpuxc)
* [Growing the Rust Community](https://www.youtube.com/watch?v=duv0tuPAnO0)
* [Rust: A Language for the Next 40 Years - Carol Nichols](https://www.youtube.com/watch?v=A3AdN7U24iU)
* [Build a cryptocurrency! - Blockchain in Rust #01: Blocks & Hashing](https://www.youtube.com/watch?v=vJdT05zl6jk)
* [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion)
* [A Case for Oxidation](https://www.youtube.com/watch?v=cDFSrVhnZKo)
* [Rust Async Programming in 2018](https://www.youtube.com/watch?v=j0SIcN-Y-LA)
* [Building Safe and Secure Systems in Rust](https://www.youtube.com/watch?v=Bja9--oD9Mo)
* [Programming in Rust 01: Warmup](https://www.youtube.com/watch?v=sv9fTlU7SCA&list=PLTOeCUgrkpMNEHx6j0vCH0cuyAIVZadnc&index=2&t=0s)
* [Advent of Code in Rust](https://www.youtube.com/playlist?list=PLIbQqI9hzo4Iy8_FUnP0LgWR6ZaRnr2XT)
* [Rust and the Future of Systems Programming](https://www.youtube.com/playlist?list=PLo3w8EB99pqJ74XIGe72c9hBZWz9Y16cY)
* [Rust Hello](https://www.youtube.com/channel/UCZ_EWaQZCZuGGfnuqUoHujw)


## Source code
* [Ripgrep](https://github.com/BurntSushi/ripgrep)
* [Diesel](https://github.com/diesel-rs/diesel)
* [Regex](https://github.com/rust-lang/regex)


## Lists
* [Rust Learning](https://github.com/ctjhoa/rust-learning)

