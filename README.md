# Curated Rust
This is a guided walkthrough of the resources that I used to learn Rust. It is being added to incrementally as I myself learn rust over the next couple of weeks and months.

It is still being worked on and not yet complete.

Some of the days, there are extra material. These are marked as *👑 Extra* and they are for material that is either not free, material that does not add something new
, or stuff that is not really relevant, but which might still be interesting.

## Table of contents
* [Week 1: Introduction and getting started](#week-1-introduction-and-getting-started)
* [Week 2: It's getting more advanced](#week-2-its-getting-more-advanced)
* [Week 3: Half way there](#week-3-half-way-there)
* [Week 4](#week-4)
* [To be organised](#to-be-organised)
* [References](#references)

## Week 1: Introduction and getting started
This is our introduction to Rust. It will cover a lot of the fundamentals and when this week is behind us, we will already be able to write software. 
During this week we will be watching video and we will be doing a bit of reading.
Some smaller exercises will also pop up during this week so get ready to code!

### Week 1, Day 1: What is Rust? (~ 1 hour)
So. For this first couple of days we will get to know a lot of things about Rust and we will get to travel 
to different parts of Rust. Try to relax. It's important that you **don't try too hard to learn anything**. 
Just sit back and try to enjoy it. Things will become more clear as we go. 

You probably won't understand all of the material for today, and that's totally fine. If you do understand everything, then great, otherwise you will find that it will all be comprehensible in time, we will come back to some of 
this material later on.

* 📺 1h 3min: Watch [Considering Rust - Jon Gjengset](https://www.youtube.com/watch?v=DnT-LUQgc7s)

### Week 1, Day 2: Getting started (~ 1 hour)
Time to get started. Start off by watching a short video on Rust. Then we continue reading through the introduction (section 1) [Introduction - The Rust Programming Language](https://doc.rust-lang.org/stable/book/ch00-00-introduction.html),
this will have you create not one, but two Hello World! apps.
We then do a bit more intro reading by reading pages sections 1 Why Rust? and 2 Type Safety from [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf).

* 📺 6 min: Watch [Rust and the Future of Systems Programming](https://www.youtube.com/watch?v=8EPsnf_ZYU0)
* 📚 20 min: Read through [Introduction - The Rust Programming Language](https://doc.rust-lang.org/stable/book/ch00-00-introduction.html) and then Section [1. Getting Started](https://doc.rust-lang.org/stable/book/ch01-00-getting-started.html).
* 📚 10 min: Read through the first and second sections of [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf); Why Rust? and Type Safety.
* 📚 10 min: Read through the introduction of [A Gentle Introduction To Rust](https://stevedonovan.github.io/rust-gentle-intro/readme.html)
* 📚 15 min: Checkout the Hello World example of [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/hello.html). Read 1.1 Comments but skip section 1.2 Formatted Print for now.

#### 👑 Extra
* 📰 15 min: Read [Understanding Over Guesswork](https://hoverbear.org/blog/understand-over-guesswork/) from [Hoverbear](https://hoverbear.org), a great read and overview of Rust. It has a lot of content that we are unfamiliar with, so try to mainly get the gist of it.


### Week 1, Day 3: Variables (~ 1 hour 10 minutes)
Now we are actually about to write our first pieces of software. Let's get into it!

* 📚 25 min: Read [2. Programming a Guessing Game](https://doc.rust-lang.org/stable/book/ch02-00-guessing-game-tutorial.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 📚 10 min: While we are talking about random stuff anyway, head over to Rust Cookbook and read [Generate random numbers](https://rust-lang-nursery.github.io/rust-cookbook/algorithms/randomness.html#generate-random-numbers). Try to understand the code, but don't spend too much time digging into the details.
* 📚 7 min: Read [3.1 Variables and Mutability](https://doc.rust-lang.org/stable/book/ch03-01-variables-and-mutability.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 💻 10 min: Setup [Rustlings](https://github.com/fmoko/rustlings).
* 💻 15 min: Do exercises *variables1*, through *variables6* from the [Rustlings](https://github.com/fmoko/rustlings) Course
* 📚 2 min: Read about [constants](https://doc.rust-lang.org/stable/rust-by-example/custom_types/constants.html) in the [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example)
* 📚 5 min: Read all the sections of [Variable Bindings](https://doc.rust-lang.org/stable/rust-by-example/variable_bindings.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/hello.html)

#### 👑 Extra
* 📰 15 min: Read [Stability as a Deliverable](https://blog.rust-lang.org/2014/10/30/Stability.html). It was a blog post made at the 1.0 release of Rust and gives you an idea about how the Rust project works.
 
### Week 1, Day 4: Types, Functions and flow control (~ 1 hour 30 minutes)
* 📚 8 min: Read [3.2 Data Types](https://doc.rust-lang.org/stable/book/ch03-02-data-types.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 💻 5 min: Read all the sections of [2. Primitives](https://doc.rust-lang.org/stable/rust-by-example/primitives.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html), skip the activity for section '2.2 Tuples' for now, we will get back to it.
* 📚 8 min: Read [3.3 Functions](https://doc.rust-lang.org/stable/book/ch03-03-how-functions-work.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html)
* 📚 1 min: Read [7. Expressions](https://doc.rust-lang.org/stable/rust-by-example/expression.html) in the [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example) 
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
We start off by looking at two presentations. I know, sometimes it's hard co stay awake going through these. Check one of them out today, and look at the other tomorrow.

* 📺 1h: Watch [What Is Rust? - Yehuda Katz](https://www.infoq.com/presentations/rust-gc/)

#### 👑 Extra
* 📰 10 min: Read [Rust is more than safety](https://words.steveklabnik.com/rust-is-more-than-safety). This blog post caused quite the stir and there was several followups to it. Read one of them next.
* 📰 10 min: Read [Rust is mostly safety](http://graydon2.dreamwidth.org/247406.html)

### Week 1, Day 6: Even more video! (~ 40 min)
Bring out the popcorn, another video, just as promised yesterday!
Don't worry if you don't understand every detail in this video. We are heading into a part of rust that many find quite confusion and hard, namely Ownership and Borrowing. These two videos; the one you watched yesterday, and the one you will be watching now, will set you up to better understand the material to come. We will be taking a couple of days to go over this area, as it is quite advanced, but also very fundamental.

*  📺 40 min: Watch [A Case for Oxidation: The Rust Programming Language - Sergio Benitez](https://www.youtube.com/watch?v=cDFSrVhnZKo)

### 👑 Extra
* 📺 5 min: Watch [Growing the Rust Community](https://www.youtube.com/watch?v=duv0tuPAnO0)

### Week 1, Day 7: Ownership and borrowing (~ 1 hour)
Take your time while reading these next chapters. They are truly fundamental and the more time you put into understanding these concepts now, the easier it will be later on.

* 📚 20 min: Read [4.1 What is Ownership?](https://doc.rust-lang.org/stable/book/ch04-01-what-is-ownership.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html).
* 📚 10 min: Read [4.2 References and Borrowing](https://doc.rust-lang.org/stable/book/ch04-02-references-and-borrowing.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html).
* 📚 10 min: Read [4.3 The Slice Type](https://doc.rust-lang.org/stable/book/ch04-03-slices.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html).
* Read the same material from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example), please note that we are skipping 15.4 Lifetimes for now, we'll get back to it.
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

### Week 2, Day 2: Structs, methods and strings (~ 1 hour, 20min)
* 📚💻 25 min: Read all the sections of [5. Using Structs to Structure Related Data](https://doc.rust-lang.org/stable/book/ch05-00-structs.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html). Follow along by writing the code yourself.
* 📚 15 min: Read section [8.2. Storing UTF-8 Encoded Text with Strings](https://doc.rust-lang.org/stable/book/ch08-02-strings.html) from [The Rust Programming Language](https://doc.rust-lang.org/stable/book/title-page.html). Don't worry about the references to *vec*, we will get to it soon.
* 📚 5 min: Read [3.1 Structures](https://doc.rust-lang.org/stable/rust-by-example/custom_types/structs.html) in [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/index.html)
* 📚 5 min: Read [9.1 Methods](https://doc.rust-lang.org/stable/rust-by-example/fn/methods.html) in [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/index.html)
* 💻 30 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *structs1*, *structs2*, *structs3*, *strings1*, *strings2* and *test2*.

We will get back to more about structs very soon. So, if you have not fully wrapped your head around all of this, don't worry.

### Week 2, Day 3: Enums and Pattern Matching (~ 1 hour, 45min)
* 📚 15 min: Read all the sections of [Enums and Pattern Matching](https://doc.rust-lang.org/book/ch06-00-enums.html) from [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html)
* 📚 10 min: Read [3.2 Enums](https://doc.rust-lang.org/stable/rust-by-example/custom_types/enum.html) from [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/)
* 📚 15 min: Read all the sections of [8.5 match](https://doc.rust-lang.org/stable/rust-by-example/flow_control/match.html) from [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/)
* 💻 20 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *enums1*, *enums2* and *enums3*.
* 📰 15 min: Read [Mixing matching, mutation, and moves in Rust](https://blog.rust-lang.org/2015/04/17/Enums-match-mutation-and-moves.html). Don't worry if you don't understand it all. It's quite a though read!
* 💻 30 min: Do the *Leap* and the *Matching Brackets* exercises on [Exercism](https://exercism.io/)

#### 👑 Extra
* 📚 2 min: Read [8.6 if let](https://doc.rust-lang.org/stable/rust-by-example/flow_control/if_let.html) from [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/)
* 📚 2 min: Read [8.7 while let](https://doc.rust-lang.org/stable/rust-by-example/flow_control/while_let.html) from [Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/)


### Week 2, Day 4: Collections and formatting (~ 1 hour, 30min)
* 📚 10 min: Read [8.1 Storing Lists of Values with Vectors](https://doc.rust-lang.org/stable/book/ch08-01-vectors.html) from [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html)
* 📚 5 min: Read [8.3 Storing Keys with Associated Values in Hash Maps](https://doc.rust-lang.org/stable/book/ch08-03-hash-maps.html) form [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html)
* 📚 15 min: Read [1.2 Formatted Print](https://doc.rust-lang.org/stable/rust-by-example/hello/print.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/primitives.html)
* 💻 10 min: Do the [Two Sum](https://leetcode.com/problems/two-sum/) problem on [Leetcode.com](https://leetcode.com). 

Now on to two exercises. They do not directly related to the topics of the day, but practicing writing code is valuable. You should have the tools to solve them.

* 💻 20 min: Do the *Robot Simulator* exercise on [Exercism](https://exercism.io/)
* 💻 30 min: Do the *Binary Search* exercise on [Exercism](https://exercism.io/)

#### 👑 Extra
* 📚 15 min: Read [Sort a vector](https://rust-lang-nursery.github.io/rust-cookbook/algorithms/sorting.html) from the Rust Cookbook. It has some lambdas in the code, just ignore them for now.
 
### Week 2, Day 5: Error Handling (~ 1 hour, 15 min)
Some find Error handling in Rust to be difficult. I should know, I am one of them. Coming from a language like Java or Python, Rust's error handling can seem obscure. I am told, however, that you get used to it and that you learn to love it. 
Let's get started!

* 📚 25 min: Read [9. Error Handling](https://doc.rust-lang.org/stable/book/ch09-00-error-handling.html) from [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html)
* 📚 20 min: Read [18. Error Handling](https://doc.rust-lang.org/stable/rust-by-example/error.html) from [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/index.html). Read all the sub sections as well. It will introduce some new material that will be useful. 
* 📰 10 min Read [On Error Handling](https://lucumr.pocoo.org/2014/10/16/on-error-handling/) from the blog *Armin Ronacher's Thoughts and Writings*
* 💻 25 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *errors1*, *errors2*, *errorsn*, *result1*.

#### 👑 Extra
* 📰 25 min: Read [Error Handling in Rust](https://blog.burntsushi.net/rust-error-handling/) from Andrew Gallant's Blog.
* 📰 25 min: Read [Rust: Error Handling](https://medium.com/learning-rust/rust-error-handling-72a8e036dd3)
* 📚 10 min: Read [Error Handling](https://stevedonovan.github.io/rust-gentle-intro/6-error-handling.html) from [A Gentle Introduction to Rust](https://stevedonovan.github.io/rust-gentle-intro/readme.html)

### Week 2, Day 6: Generic Types, Traits and Lifetimes (~ 1 hour, 35min)
Traits are pretty straight forward, so it lifetimes. At least in our first pass of them. We will come back to them later to dig more into the nitty gritty.
You will find that the concepts here are pretty easy to grasp, but beneath the simple facade there lies a much more complex and intricate structure.
Up until this point, what we have learned has been pretty much what we would lean in other languages as well. But once we get into Lifetimes, we are in uncharted territory. 

* 📚 25 min: Read [10. Generic Types, Traits, and Lifetimes](https://doc.rust-lang.org/stable/book/ch10-00-generics.html) from [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html)
* 📚 10 min: Read through section Reading Rust from [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf). This has some material that you will know since before, but it does'nt hurt to repeat it.
* 📚 20 min: Read [14. Generics from Rust by Example](https://doc.rust-lang.org/stable/rust-by-example/generics.html), it goes a bit deeper.
* 📚 20 min: Read entire section of [16 Traits](https://doc.rust-lang.org/stable/rust-by-example/traits.html). **Except for** *16.5 Iterators*, we will cover Iterators* next week, and *16.6 impl Trait*, which we will also cover later. Lot's of good examples in this part of the book. Pay special attention to anything related to ```Box``` and ```dyn```.
* 💻 20 min: Do [Rustlings](https://github.com/fmoko/rustlings) exercises *traits1*, *traits2*, *generics1*, *generics2*, *generics3*

#### Extra
* 📰 10 min: Read [Rust's Built-in Traits, the When, How & Why](https://llogiq.github.io/2015/07/30/traits.html)
* 📰 10 min: Read [Rust, Lifetimes, and Collections](http://cglab.ca/~abeinges/blah/rust-lifetimes-and-collections/)
* 📰 10 min: Read [Rust, Generics, and Collections](http://cglab.ca/~abeinges/blah/rust-generics-and-collections/)

### Week 2, Day 7: More traits and life-times
* 📚 15 min: Read [15.4 Lifetimes from Rust by Example](https://doc.rust-lang.org/rust-by-example/scope/lifetime.html).
* 📚 15 min: Read through [Basics A Gentle Introduction to Rust](https://stevedonovan.github.io/rust-gentle-intro/2-structs-enums-lifetimes.html). You have seen all of this material before, but this is for hammering it into our heads. Enjoy!
* 📚 20 min: Read through [Strucs, Enums and Matching from A Gentle Introduction to Rust](https://stevedonovan.github.io/rust-gentle-intro/2-structs-enums-lifetimes.html). Same thing here. No new material, we keep on rehearsing!

#### Extra
* 💻 40 min: Do [Advent of Code 2018 Day 1](https://adventofcode.com/2018/day/1), you should know everything you need for this one. It does not teach you anything new about Rust, but it should get you more comfortable writing code. Also, if you struggle, try Googling for help, or turn to Reddit for help. We have not yet covered how to find your way around the Rust documentation, but that is coming very soon!


## Week 3: Half way there
We have passed the half-way point of the foundation. When this week is done, we will have covered all the essentials. From that point on our learning will change somewhat. We will write more code ourselves and the material we are reading will change. We will be going into depth.
But for now, let's hunker down and get through more new material. But first...

### Week 3, Day 1: A breather (~ 1 hour, 30min)
Today we will sit back and watch video again. Bring out the popcorn.
Again, as usual, don't worry too much if you don't understand all the details. Some of the things covered in this video are things we have yet to encounter in our reading.

* 📺 1h 32min: Watch [Rust Programming Techniques](https://www.youtube.com/watch?v=vqavdUGKeb4). 

### Week 3, Day 1: Iterators and closures
https://blog.guillaume-gomez.fr/articles/2017-03-09+Little+tour+of+multiple+iterators+implementation+in+Rust
http://xion.io/post/code/rust-iter-patterns.html
https://hermanradtke.com/2015/06/22/effectively-using-iterators-in-rust.html

### Week 3, Day 2: Itertools
### Week 3, Day 3: Coding!
### Week 3, Day 4: Back to ownership
Today we are going to to a lot of reading. In fact, most pieces of the puzzle is already in place. Today we will be reading blog posts on ownership. It's always good to see others perspectives.

* 📰 15 min: Read [Lock-freedom without garbage collection](https://aturon.github.io/blog/2015/08/27/epoch/)
* 📰 10 min: [Where Rust Really shines](https://manishearth.github.io/blog/2015/05/03/where-rust-really-shines/)
* 📰 15 min: Read [Rust Means Never Having to Close a Socket](https://blog.skylight.io/rust-means-never-having-to-close-a-socket/)
* 📰 10 min: Read [The Problem With Single-threaded Shared Mutability](https://manishearth.github.io/blog/2015/05/17/the-problem-with-shared-mutability/)
* 📰 5 min: Read [Strategies for solving 'cannot move out of' borrowing errors in Rust](https://hermanradtke.com/2015/06/09/strategies-for-solving-cannot-move-out-of-borrowing-errors-in-rust.html)
* 📰 5 min: Read [Graphical depiction of ownership and borrowing in Rust](https://rufflewind.com/2017-02-15/rust-move-copy-borrow)

### Week 3, Day 5: 
### Week 3, Day 6: 
### Week 3, Day 7: 

## Week 4
It is time to take a break. No, really.
When I got to this point, I was a bit sick and tired of all the reading. I wanted to build something. If you are feeling the same way, go ahead and do that. You still don't have all the pieces to the puzzle for completing a full-fledged app. But you can get quiet far. Practice makes perfect. 
Take a break. Go build something (and please share it with me when you are done!), and then get back here to continue the journey.

## Reference
### Video
- [Considering Rust - Jon Gjengset](https://www.youtube.com/watch?v=DnT-LUQgc7s)
- [Rust and the Future of Systems Programming](https://www.youtube.com/watch?v=8EPsnf_ZYU0)
- [What Is Rust? - Yehuda Katz](https://www.infoq.com/presentations/rust-gc/)
- [A Case for Oxidation: The Rust Programming Language - Sergio Benitez](https://www.youtube.com/watch?v=cDFSrVhnZKo)
- [Growing the Rust Community](https://www.youtube.com/watch?v=duv0tuPAnO0)
- [Learning Rust: Memory, Ownership and Borrowing](https://www.youtube.com/watch?v=8M0QfLUDaaA)

### Books and courses
- [The Rust Programming Language](https://doc.rust-lang.org/stable/book/ch00-00-introduction.html)
- [Why Rust?](https://www.oreilly.com/programming/free/files/why-rust.pdf)
- [A Gentle Introduction To Rust](https://stevedonovan.github.io/rust-gentle-intro/readme.html)
- [Rust By Example](https://doc.rust-lang.org/stable/rust-by-example/hello.html)
- [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/about.html)

### Articles
- [Understanding Over Guesswork](https://hoverbear.org/blog/understand-over-guesswork/)
- [Stability as a Deliverable](https://blog.rust-lang.org/2014/10/30/Stability.html)
- [Rust is more than safety](https://words.steveklabnik.com/rust-is-more-than-safety)
- [Rust is mostly safety](http://graydon2.dreamwidth.org/247406.html)
- [Rust ownership, the hard way](https://chrismorgan.info/blog/rust-ownership-the-hard-way/)
- [A closer look at Ownership in Rust](https://blog.thoughtram.io/ownership-in-rust/)
- [Mixing matching, mutation, and moves in Rust](https://blog.rust-lang.org/2015/04/17/Enums-match-mutation-and-moves.html)
- [On Error Handling](https://lucumr.pocoo.org/2014/10/16/on-error-handling/)
- [Error Handling in Rust](https://blog.burntsushi.net/rust-error-handling/)
- [Rust: Error Handling](https://medium.com/learning-rust/rust-error-handling-72a8e036dd3)
- [Rust's Built-in Traits, the When, How & Why](https://llogiq.github.io/2015/07/30/traits.html)
- [Rust, Lifetimes, and Collections](http://cglab.ca/~abeinges/blah/rust-lifetimes-and-collections/)
- [Rust, Generics, and Collections](http://cglab.ca/~abeinges/blah/rust-generics-and-collections/)

### Exercises
- [Rustlings](https://github.com/fmoko/rustlings)
- [Advent Of Code](https://adventofcode.com/)
- [Exercism](https://exercism.io/)
- [Project Euler](https://projecteuler.net)
- [Leetcode.com](https://leetcode.com)

## Todo
* Packages, crates and modules
* More on crates and Rust documentation
* Tests
* Basic I/O
* Deep dive into Lifetimes

* Concurrency and threads
* Networking
* Building a webserver
* Improving our webserver
* Channels
* Building a TCP/IP Server
* Building a TCP/IP Server continued.
* Async/Await
* Async/Await continued.
* I/O and Tokio
* Filesystem and Processes
* Understanding Ripgrep
* Box, heap and pointers
* Macros
* Regular expressions
* Reading code Regex
* Rocket
* CSV Files
* WASM
* Reading code Ripgrep
* Databases, postgres
* Databases, redis
* Reading code Diesel
* Advanced Traits
* Python and Rust
* C and Rust
* C++ and Rust
* Java & Rust
* A bit bigger app
* Serde
* rand
* tokio
* async
* clap
* regex
* log
* futures
* hyper
* lazy_static
* Clippy


## Lifetimes revisited
[Crust of Rust: Lifetime Annotations](https://www.youtube.com/watch?v=rAl-9HwD858)

### Unsafe 
https://www.ralfj.de/blog/2016/01/09/the-scope-of-unsafe.html

### Wrapper types
https://manishearth.github.io/blog/2015/05/27/wrapper-types-in-rust-choosing-your-guarantees/ 

### Random
[Idiomatic Rust](https://github.com/mre/idiomatic-rust)
[Rust Anthology Master List](https://github.com/brson/rust-anthology/blob/master/master-list.md)

https://gist.github.com/brson/a324c83a6af6a8a78dfaa9d33eb9b48e

https://techyaks.com/rust-all-ldconf.html

Video about memory safety etc. 38 minutes. [A Case for Oxidation](https://www.youtube.com/watch?v=cDFSrVhnZKo)

Video about ownership and borrowing. 1h.
Watch [What is Rust?](https://www.infoq.com/presentations/rust-gc/) [Video 1h]



### Web application / Project
* [A web application completely in Rust](https://medium.com/@saschagrunert/a-web-application-completely-in-rust-6f6bdb6c4471)
* [Rust Solution to the Mars Rover Challenge](https://github.com/cobbinma/mars_rover_/blob/master/README.md)


