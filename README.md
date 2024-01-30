<!-- 
⚠️⚠️ WARNING: This file is generated by `make render`. Do not edit manually!
See `CONTRIBUTING.md` for more information.
-->

![Logo](assets/cover.jpg)

[![Check Links](https://github.com/mre/idiomatic-rust/workflows/Check%20Links/badge.svg)](https://github.com/mre/idiomatic-rust/actions/workflows/check_links.yml)

This repository collects resources for writing clean, idiomatic Rust code. [Please bring your own.](https://github.com/mre/idiomatic-rust/blob/master/CONTRIBUTING.md) :blush:

> *Idiomatic* coding means following the conventions of a given language. It is
> the most concise, convenient, and common way of accomplishing a task in that
> language, rather than forcing it to work in a way the author is familiar with
> from a different language. - Adapted from [Tim
> Mansfield](https://github.com/tim-hr/stuff/wiki/Idiomatic-coding)

## ⚙ Projects

* [blessed.rs](https://blessed.rs) - An unofficial guide to the Rust ecosystem. Suggestions for popular, well-maintained crates.
* [cheats.rs - Idiomatic Rust tips](https://cheats.rs) - A list of quick tips to make your code more idiomatic.
* [clippy](https://github.com/rust-lang/rust-clippy) - A bunch of lints to catch common mistakes and improve your Rust code.
* [Elements of Rust](https://github.com/ferrous-systems/elements-of-rust) - A collection of software engineering techniques for effectively expressing intent with Rust.
* [Patterns](https://rust-unofficial.github.io/patterns/) - A catalogue of design patterns in Rust.
* [Possible Rust](https://www.possiblerust.com/) - A blog for intermediate Rust programmers exploring real-world code and design patterns.
* [Rust Anthology](https://github.com/brson/rust-anthology) - The best short-form writing about Rust, collected.
* [Rust API Guidelines](https://rust-lang.github.io/api-guidelines/) - An extensive list of recommendations for idiomatic Rust APIs.
* [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - A community driven collection of example code which follow Rust best practices.

## 🏋 Workshops

* [Build your own JIRA with Rust](https://github.com/LukeMathWalker/build-your-own-jira-with-rust/) - A test-driven workshop to learn Rust by building your own JIRA clone!
* [Comprehensive Rust](https://github.com/google/comprehensive-rust) - A four day Rust course developed by the Android team, covering all aspects of Rust.
* [Ferrous Systems Teaching Material](https://ferrous-systems.github.io/teaching-material/index.html) - Free workshop material produced by Ferrous Systems for trainings.
* [PingCAP talent plan](https://github.com/pingcap/talent-plan) - A series of training courses about writing distributed systems in Rust.
* [Procedural Macros Workshop](https://github.com/dtolnay/proc-macro-workshop) - A selection of projects designed to learn to write Rust procedural macros.
* [Rust 101](https://101-rs.tweede.golf/) - A Rust University course by tweede golf.
* [Rust Development at Sentry](https://develop.sentry.dev/rust/) - A document containing useful resources for getting started with Rust and adhering to Sentry coding principles.
* [rust-lang/rustlings](https://github.com/rust-lang/rustlings) - Small exercises to get you used to reading and writing Rust code.

## 📖 Books

* [Command Line Applications in Rust](https://rust-cli.github.io/book) - A tutorial on how to write CLI apps in Rust, learning many aspects of the ecosystem.
* [Command-Line Rust](https://github.com/kyclark/command-line-rust) - Learn the language by writing Rust versions of common Unix coreutils.
* [Discover the world of microcontrollers through Rust!](https://rust-embedded.github.io/discovery/) - An introductory course on microcontroller-based embedded systems using Rust.
* [High Assurance Rust](https://highassurance.rs/) - Developing secure and robust software, focusing on embedded-friendly data structures in Rust.
* [Programming Rust: Fast, Safe Systems Development](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/) - A comprehensive Rust Programming Guide that covers most of Rust's features in detail.
* [Rust Atomics and Locks](https://marabos.nl/atomics/) - Helps Rust programmers of all levels gain a clear understanding of low-level concurrency.
* [Rust Cookbook](https://github.com/rust-lang-nursery/rust-cookbook) - Examples that demonstrate good practices to accomplish common programming tasks in Rust.
* [Rust for Rustaceans](https://nostarch.com/rust-rustaceans) - Covers how to design reliable, idiomatic, and ergonomic Rust programs based on best principles.

## 📰 Articles

### 2023

* [Aim For Immutability in Rust](https://corrode.dev/blog/immutability/) - Explains why variables are immutable in Rust by default.
* [Compile-Time Invariants in Rust](https://corrode.dev/blog/compile-time-invariants/) - Shows how macros can be used to enforce invariants at compile-time.

### 2021

* [Hexagonal architecture in Rust](https://alexis-lozano.com/hexagonal-architecture-in-rust-1/) - Describes how to build a Rust service using domain driven design and a test-first approach.
* [Wrapping errors in Rust](https://edgarluque.com/blog/wrapping-errors-in-rust) - Wrapping 'reqwest::Error' and a custom error type as an enum to make library usage easier.
* [Aiming for idiomatic Rust](https://web.archive.org/web/20221203043933/https://shane-o.dev/blog/aiming-for-idiomatic-rust) - Discusses different ways to solve a popular coding puzzle, 'balanced brackets', in Rust.
* [Naming Your Lifetimes](https://www.possiblerust.com/pattern/naming-your-lifetimes) - Explains how using longer, declarative lifetime names can help to disambiguate which borrow is which.

### 2020

* [Are out parameters idiomatic in Rust?](https://steveklabnik.com/writing/are-out-paramters-idiomatic-in-rust) - Discusses the pros and cons of functions returning a value vs. modifying a parameter in-place.
* [Guide on how to write documentation for a Rust crate](https://blog.guillaume-gomez.fr/articles/2020-03-12+Guide+on+how+to+write+documentation+for+a+Rust+crate) - Writing good documentation with rustdoc including many examples.
* [Learning Rust through open source and live code reviews](https://loige.co/learning-rust-through-open-source-and-live-code-reviews/) - Covers patterns like 'FromStr' and exposing a CLI and a library in one crate.
* [Refactoring Rust Transpiled from C](https://immunant.com/blog/2020/09/transpiled_c_safety/) - Describes how to lift a C-project that was automatically converted to unsafe Rust to safer, more idiomatic Rust.
* [Context-preserving error handling](https://kazlauskas.me/entries/errors) - Explains how to use crates like 'thiserror' in combination with 'map_err' to add context to errors.

### 2019

* [Rust Patterns: Enums Instead Of Booleans](http://blakesmith.me/2019/05/07/rust-patterns-enums-instead-of-booleans.html) - Discusses how using enums instead of booleans can express intent more clearly in Rust.
* [Taking string arguments in Rust](http://xion.io/post/code/rust-string-args.html) - Discussing how to avoid subtle issues with string handling and when to use 'str' vs 'String'.
* [Await a minute](https://docs.rs/dtolnay/0.0.3/dtolnay/macro._01__await_a_minute.html) - Example code for moving from raw futures to async/await syntax to improve error handling.

### 2018

* [Programming an ARM microcontroller in Rust at four different levels of abstraction](https://pramode.in/2018/02/20/programming-a-microcontroller-in-rust-at-four-levels-of-abstraction/) - Demonstrates how Rust helps to move from low-level embedded code to high-level abstractions.

### 2017

* [The balance between cost, useability and soundness in C bindings, and Rust-SDL2's release](https://web.archive.org/web/20190509123207/https://cobrand.github.io/rust/sdl2/2017/05/07/the-balance-between-soundness-cost-useability.html) - Writing safe, sound, idiomatic libraries despite the limitations of the borrow checker.
* [Math with distances in Rust: safety and correctness across units](https://ferrisellis.com/content/rust-implementing-units-for-types/) - How to create a system to cleanly and safely do arithmetic with lengths.
* [Lessons learned redesigning and refactoring a Rust Library](https://web.archive.org/web/20220126172949/https://blog.mgattozzi.dev/refactor-rust/) - 'RefCell', the builder pattern and more.
* [Iteration patterns for Result & Option](http://xion.io/post/code/rust-iter-patterns.html) - Explores how to filter and partition iterators of Result and Option types idiomatically.

### 2016

* [Idiomatic tree and graph like structures in Rust](https://rust-leipzig.github.io/architecture/2016/12/20/idiomatic-trees-in-rust/) - Introduction to safe, dynamic, arena based tree structures without using lifetimes.
* [Convenient and idiomatic conversions in Rust](https://ricardomartins.cc/2016/08/03/convenient_and_idiomatic_conversions_in_rust) - Explains 'From<T>', 'Into<T>', 'TryFrom<T>', 'TryInto<T>', 'AsRef<T>' and 'AsMut<T>' with practical examples.
* [Rustic Bits](https://llogiq.github.io/2016/02/11/rustic.html) - Small things that make for rustic code.
* [Ripgrep Code Review](https://blog.mbrt.dev/posts/ripgrep/) - An analysis of the popular 'ripgrep' tool's source code.
* [Pretty State Machine Patterns in Rust](https://hoverbear.org/2016/10/12/rust-state-machine-pattern/) - How to represent a State Machine in an expressive and understandable way in Rust.
* [Teaching libraries through good documentation](https://deterministic.space/teaching-libraries.html) - How to use the full power of Rust's documentation support (e.g. doc tests).
* [Elegant Library APIs in Rust](https://deterministic.space/elegant-apis-in-rust.html) - Many helpful tips and tricks for writing libraries in Rust.
* [Russian Dolls and clean Rust code](https://web.archive.org/web/20220126183049/https://blog.mgattozzi.dev/russian-dolls/) - How to use the full power of 'Option' and 'Result' (especially 'and_then()' and 'unwrap_or()').

### 2015

* [Rayon: data parallelism in Rust](https://smallcultfollowing.com/babysteps/blog/2015/12/18/rayon-data-parallelism-in-rust/) - Writing elegant parallel code in Rust.
* [Strategies for solving 'cannot move out of' borrowing errors in Rust](https://hermanradtke.com/2015/06/09/strategies-for-solving-cannot-move-out-of-borrowing-errors-in-rust.html) - Practical tips to help understand the borrow-checker and move semantics.
* [Effectively Using Iterators In Rust](https://hermanradtke.com/2015/06/22/effectively-using-iterators-in-rust.html) - Explanation of the 'Iter' and 'IntoIter' traits and how loops actually work in Rust.
* [Creating a Rust function that returns a &str or String](https://hermanradtke.com/2015/05/29/creating-a-rust-function-that-returns-string-or-str.html) - How 'Into' and 'Cow' (Clone-on-write) work together to avoid allocations for string types.
* [Creating a Rust function that accepts String or &str](https://hermanradtke.com/2015/05/06/creating-a-rust-function-that-accepts-string-or-str.html) - How to make calling your code both ergonomic and fast (zero-allocation).
* [Error Handling in Rust](https://blog.burntsushi.net/rust-error-handling/) - Understanding and handling errors in Rust in an idiomatic way.
* [Rust traits for developer friendly libraries](https://benashford.github.io/blog/2015/05/24/rust-traits-for-developer-friendly-libraries/) - Thoughts about implementing good Rust libraries.


## 🎤 Talks

### 2023

* Tricks of the Trait: Enabling Ergonomic Extractors - Rust Nation UK, Feb. 2023 [[Video](https://www.youtube.com/watch?v=7DOYtnCXucw)]

### 2022

* Ergonomic APIs for hard problems - RustLab Conference, October 2022 [[Video](https://www.youtube.com/watch?v=Phk0C-kLlho)]
* Nine Rules for Elegant Rust Library APIs - Seattle Rust Meetup, Sep. 2022 [[Video](https://www.youtube.com/watch?v=6-8-9ZV-2WQ)]

### 2020

* Macros for a More Productive Rust - RustConf 2020 [[Video](https://www.youtube.com/watch?v=dZiWkbnaQe8)]

### 2019

* Making Rust Delightful - RustCon Asia 2019 [[Video](https://www.youtube.com/watch?v=YSEx8wtlPWc)]

### 2018

* Idiomatic Rust - Writing Concise and Elegant Rust Code - FOSDEM 2018 [[Video](https://www.youtube.com/watch?v=P2mooqNMxMs)]

### 2017

* Idiomatic Rust Libraries - Rustfest Kiev [[Video](https://www.youtube.com/watch?v=0zOg8_B71gE)]


## 💬 Forum

### 2020

* [Preferred way of passing `Path`-like types around?](https://www.reddit.com/r/rust/comments/cekeq9/preferred_way_of_passing_pathlike_types_around/)

### 2017

* [An idiomatic way to sum up values in a multidimensional Array](https://users.rust-lang.org/t/an-idiomatic-way-to-sum-up-values-in-a-multidimensional-array/9485)
* [Which is more idiomatic? Functional, imperative or a mix?](https://users.rust-lang.org/t/which-is-more-idiomatic-functional-imperative-or-a-mix/11278)


## 📜 History

Coming from Python, I loved the guidelines on how *idiomatic Python* looks like. I was inspired by the likes of Peter Norvig, who wrote amazing articles on [spellcheckers](https://norvig.com/spell-correct.html) and [sudoku solvers](https://norvig.com/sudoku.html); and, of course, the [Zen of Python](https://www.python.org/dev/peps/pep-0020/). For Rust, there is no such thing as the Zen of Python, however, so I started collecting my own resources.
The goal of this project is to create a peer-reviewed collection of articles/talks/repos, which teach idiomatic Rust style. It's a community project and you can contribute.

## 🔏 License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Matthias Endler](https://endler.dev) has waived all copyright and related or neighboring rights to this work.
Logo adapted from [FreePik.com](https://www.freepik.com/free-vector/crabs-pattern-design_1093131.htm).
