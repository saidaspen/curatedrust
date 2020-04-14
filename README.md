# Curated Rust
This is a list of resources that I used to learn Rust. It is being added to incrementally as I myself learn rust over the next couple of months and weeks.

Some of the days, there are extra material. This is for material that is either not free, material that does not add anything new
, or only elaborated on previously covered topics.

## Week 1: Introduction and getting started
This is our introduction to Rust. We will be watching a lot of video and we will be doing a bit of reading.
Some smaller exercises will also pop up during this week.

### Day 1: What is Rust? (~ 1 hour)
So. For this first couple of days we will get to know a lot of things about Rust and we will get to travel 
to different parts of Rust. Try to relax. It's important that you **don't try too hard to learn anything**. 
Just sit back and try to enjoy it. Things will become more clear as we go. 

You probably won't understand all of the material for today, and that's totally fine. If you do understand everything, then great, otherwise you will find that it will all be comperhensible in time, we will come back to some of 
this material later on.

* 📺 1h 3min: Watch [Considering Rust - Jon Gjengset](https://www.youtube.com/watch?v=DnT-LUQgc7s)

### Day 2: Getting started (~ 1 hour)
Time to get started. Start off by watching a short video on Rust. Then we continue reading through the introduction (section 1) [Introduction - The Rust Programming Language](https://doc.rust-lang.org/stable/book/ch00-00-introduction.html),
this will have you create not one, but two Hello World! apps.
We then do a bit more intro reading by reading pages sections 1 Why Rust? and 2 Type Safety from [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf).

* 📺 6 min: Watch [Rust and the Future of Systems Programming](https://www.youtube.com/watch?v=8EPsnf_ZYU0)
* 📚 20 min: Read through [Introduction - The Rust Programming Language](https://doc.rust-lang.org/stable/book/ch00-00-introduction.html)
* 📚 10 min: Read through the first and second secions of [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf); Why Rust? and Type Safety.
* 📚 10 min: Read through the introduction of [A Gentle Introduction To Rust](https://stevedonovan.github.io/rust-gentle-intro/readme.html)
* 📚 15 min: Checkout the Hello World example of [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/hello.html). Read 1.1 Comments but skip section 1.2 Formatted Print for now.

### Day 3: Variables (~ 1 hour 10 minutes)
Now we are actually about to write our first pieces of software. Let's get into it!

* 📚 25 min: Read [2. Programming a Guessing Game](https://doc.rust-lang.org/stable/book/ch02-00-guessing-game-tutorial.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 📚 10 min: While we are talking about random stuff anyway, head over to Rust Cookbook and read [Generate random numbers](https://rust-lang-nursery.github.io/rust-cookbook/algorithms/randomness.html#generate-random-numbers). Try to understand the code, but don't spend too much time digging into the details.
* 📚 7 min: Read [3.1 Variables and Mutability](https://doc.rust-lang.org/stable/book/ch03-01-variables-and-mutability.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 💻 10 min: Setup [Rustlings](https://github.com/fmoko/rustlings).
* 💻 15 min: Do exercises *variables1*, through *variables6* from the [Rustlings](https://github.com/fmoko/rustlings) Course
* 📚 2 min: Read about [constants](https://doc.rust-lang.org/stable/rust-by-example/custom_types/constants.html) in the [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example)
* 📚 5 min: Read all the sections of [Variable Bindings](https://doc.rust-lang.org/stable/rust-by-example/variable_bindings.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/hello.html)

### Day 4: Types, Functions and flow control (~ 1 hour 30 minutes)
* 📚 8 min: Read [3.2 Data Types](https://doc.rust-lang.org/stable/book/ch03-02-data-types.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 💻 5 min: Read all the sections of [2. Primitives](https://doc.rust-lang.org/stable/rust-by-example/primitives.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html), skip the activity for section '2.2 Tuples' for now, we will get back to it.
* 📚 8 min: Read [3.3 Functions](https://doc.rust-lang.org/stable/book/ch03-03-how-functions-work.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 📚 1 min: Read [7. Expressions](https://doc.rust-lang.org/stable/rust-by-example/expression.html) in the [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html) 
* 📚 1 min: Read [3.4 Comments](https://doc.rust-lang.org/stable/book/ch03-04-comments.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 📚 1 min: Read [1.1 Comments](https://doc.rust-lang.org/stable/rust-by-example/hello/comment.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html)
* 📚 10 min: Read [3.5 Control Flow](https://doc.rust-lang.org/stable/book/ch03-05-control-flow.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html). Do not do the exercises at the very end, we will do them in a minute, but first read about control flow also in Rust By Example.
* 💻 10 min: Read sections [8.1 if/else] (https://doc.rust-lang.org/stable/rust-by-example/flow_control/if_else.html) through [8.4 for and range](https://doc.rust-lang.org/stable/rust-by-example/flow_control/for.html) of [Rust By Example]. Go ahead and write up your own version of FizzBuzz!
* Go back to to [the Summary of 3.5 Control Flow](https://doc.rust-lang.org/stable/book/ch03-05-control-flow.html#summary) and implement those three small programs:
  - 💻 5 min: Convert temperatures between Fahrenheit and Celsius
  - 💻 15 min: Generate the nth Fibonacci number
  - 💻 15 min: Print the lyrics to the Christmas carol "The Twelve Days of Christmas"
* 💻 15 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *If1*, *functions1* through *functions5*, *test1* and *primitive_types1*, *primitive_types2*. Stop there, we will continue with *primitive_types3* later on.

### Day 5: Functions
### Day 6: Control Flow
### Day 7: Type to put it all together
----



## To be sorted
When we have done structs:
* 💻 min: Read [1.2 Formatted Print](https://doc.rust-lang.org/stable/rust-by-example/hello/print.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html)


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

